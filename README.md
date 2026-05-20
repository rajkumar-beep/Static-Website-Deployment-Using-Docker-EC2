# Static Website Deployment Using Docker + EC2

## Technologies Used
- Docker
- AWS EC2
- GitHub
- Nginx

## Project Flow
HTML Website → Docker → GitHub → AWS EC2

## Commands Used

docker build -t static-website .

docker run -d -p 80:80 static-website

## Deploy on AWS EC2

Launch EC2 then install Docker and git.
Pull the code from repo. Build the image and run
