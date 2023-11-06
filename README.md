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

Evidencias de la Réplica:
- Código:
https://github.com/sebas2503/ComputacionParalelaProyecto/assets/62064772/dc359e6a-d2d8-4a5c-ae79-d9f64900746f

- Compilación:


https://github.com/sebas2503/ComputacionParalelaProyecto/assets/62064772/249336b1-9b8e-460a-9be8-7695bb4aaad3


