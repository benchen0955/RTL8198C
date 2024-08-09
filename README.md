# RTL8198C
# cross compiler
8198c_toolchain/toolchain/msdk-4.4.7-mips-EB-3.10-0.9.33-m32t-131227b/bin/msdk-linux-gcc -L/8198c_toolchain/msdk-4.4.7-mips-EB-3.10-0.9.33-m32t-131227b/lib -wl,-rpath/8198c_toolchain/msdk-4.4.7-mips-EB-3.10-0.9.33-m32t-131227b/lib

/home/kk/8198c_toolchain/toolchain/msdk-4.4.7-mips-EB-3.10-0.9.33-m32t-131227b/bin/msdk-linux-gcc -L/home/kk/8198c_toolchain/toolchain/msdk-4.4.7-mips-EB-3.10-0.9.33-m32t-131227b/lib -Wl,-rpath=/home/kk/8198c_toolchain/toolchain/msdk-4.4.7-mips-EB-3.10-0.9.33-m32t-131227b/lib ca.c libapmib.so CA_src/lib_bin/getCA_8198.o CA_src/lib_bin/get_CA_expireDate_8198.o  -lssl -lcrypto -lcurl -o fw_data/ca_8198c
