# Docker run
    docker run -d -p 80:80 jeftadirksen/myip

# Docker build
    git clone https://github.com/JeftaDirksen/MyIP.git
    cd MyIP
    docker build -t myip .
    docker run -d -p 80:80 myip
