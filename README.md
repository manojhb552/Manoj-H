# Manoj-H
# A 4-week Research Internship on RISC-V using VSDSquadron Mini RISC-V Dev Board
<details>
  
<summary><b>Task 1:</b></summary>

install RISC-V GNU Toolchain

install Yosys

install iverilog

install gtkwave

# CLONING RISC-V GNU TOOLCHAIN

sudo apt install git-all # To install git

sudo apt-get install autoconf automake autotools-dev curl python3 libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool patchutils bc zlib1g-dev libexpat-dev make sure to install the dependencies
![riscv](https://github.com/manojhb552/Manoj-H/assets/154490935/4257ff16-e096-4527-8a48-393255067d6d)

# Create a opt dir
mkdir /opt/riscv try sudo incase of permission denial

In my case I created a driectory mkdir riscv 
![riscv2](https://github.com/manojhb552/Manoj-H/assets/154490935/34cec089-c85c-46ff-864f-afd145e71eb7)

# INSTALLING IVERILOG GTKWAVE & YOSYS

# YOSYS

git clone https://github.com/YosysHQ/yosys.git
cd yosys 
sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev\libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make 
sudo make install
![yosys](https://github.com/manojhb552/Manoj-H/assets/154490935/b2f2f7f8-80ac-48ff-a83c-a8e82c98fe22)

# iVerilog

sudo apt-get install iverilog
![iverilog](https://github.com/manojhb552/Manoj-H/assets/154490935/40061254-bd60-464e-b768-498cfa4711f4)

# GTkWave

sudo apt-get install gtkwave

![gtk](https://github.com/manojhb552/Manoj-H/assets/154490935/d7514d6e-02fa-49df-988b-1fbfdcde3cf8)

