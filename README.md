# ComputacionParalelaProyecto

1.Instalar Ubuntu 20.04 lts de windows store

2. Instalar g++ : sudo apt install g++
 
3. Instalar nvidia tool kit: 
  sudo apt update
  sudo apt upgrade
  sudo apt install nvidia-cuda-toolkit


4. Verificar version: nvcc --version
   
5. Compilar codigo: nvcc -O3 -arch=sm_35 ECL-GC_12.cu -o ecl-gc
   
6. Compilar ejecutable: ./ecl-gc fileGraph (ejemplo: ./ecl-gc amazon0601.egr)
