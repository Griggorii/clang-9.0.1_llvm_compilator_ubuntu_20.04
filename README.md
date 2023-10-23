# clang-9.0.1_llvm_compilator_ubuntu_20.04
clang-cpp , libllvm , clang-cl , lld  , libclang_rt.fuzzer-x86_64.a , ldb , c++ v1 experimental , clang-c , llvm-c , polly

clang-9.0.1_llvm-cros_Ubuntu_20.04.tar.gz | size 4.2 Gb unpack 20 Gb

Download link clang-9.0.1 https://dropmefiles.com/IYKye

md5sum 6b98742a028d0d650872008fdce5f4f7 'clang-9.0.1_llvm-cros_Ubuntu_20.04.tar.gz'

sudo tar xvf clang-9.0.1_llvm-cros_Ubuntu_20.04.tar.gz -C/

sudo ln -s 

Example configure

./configure CXX=/usr/lib/llvm-9/bin/clang++ --flag_1 --flag2

and

./configure CC=/usr/lib/llvm-9/bin/clang-cpp CXX=/usr/lib/llvm-9/bin/clang++ --flag_1 --flag2

Cmake example

CC=/usr/lib/llvm-9/bin/clang-cpp CXX=/usr/lib/llvm-9/bin/clang++                                \
cmake -DCMAKE_INSTALL_PREFIX=/usr               \
      -DLLVM_GRIGGORII_EXAMPLE=ON                 \
      -Wno-dev -G Ninja ..                      &&
ninja



