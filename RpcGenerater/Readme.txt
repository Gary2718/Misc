使用命令 (需修改路径）
goopal_api_generator.exe "--api-classname=CommonApi" "--api-interface-output-dir=./bin_test" "--rpc-stub-output-dir=rpc_stubs" "./blockchain_api.json" "./network_api.json" "./debug_api.json" "./delegate_api.json" "./wallet_api.json" "./general_api.json" "./contract_api.json" "./script_api.json" "./types.json"

生成rpc_stub文件和common_api.hpp  
生成后放入对应的源码路径:     
common_api.hpp 放在 D:\GRBit_ver1\grbit\libraries\api\include\goopal\api
rpc_stub文件夹放在 D:\GRBit_ver1\grbit\libraries




如果需要修改api接口，修改对于的api cpp源码， 再修改对应的api的json文件，使用上述参数命令产生生成rpc_stub文件和common_api.hpp ，放入对应的源码路径， 再重新编译 。