# macos-siesta-parallel
To install siesta parallel version in Macos M1/2

brew install scalapack laapack open-mpi 

wget https://gitlab.com/siesta-project/siesta/-/releases/v4.1.5/downloads/siesta-4.1.5.tar.gz

tar -zxvf siesta-4.1.5.tar.gz

cd siesta-4.1.5/Obj

sh ../Src/obj_setup.sh

cp arch.make siesta-4.1.5/Obj


## Pay attention to modify the scalapack and laapack's path in  arch.make ##

make

Good Luck
