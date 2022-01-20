# SINTAKS DOCKER

### 1. Sintaks untuk memulai docker kontainer di backgroud
docker run -d nama_kontainer

### 2. Sintaks untuk memulai docker kontainer sekali hapus
docker run -rm nama_kontainer

### 3. Sintaks untuk memulai interaktif kontainer
docker run -it nama_kontainer

### 4. Sintaks untuk memberi nama kontainer
docker run --name nama_kontainer

### 5. Sintaks untuk memulai docker kontainer yang berhenti
docker start nama_kontainer

### 6. Sintaks untuk menghentikan docker kontainer
docker stop nama_kontainer

### 7. Sintaks untuk melihat daftar kontainer yang aktif
 + docker container ls
 + docker ps
 
### 8. Sintaks untuk melihat semua daftar kontainer 
 + docker container ls -a / -all
 + docker ps -a
 
### 9. Sintaks melihat daftar images
docker images
docker image ls

### 10. Sintaks melihat info tentang images(port, info)
docker inspect nama_images













