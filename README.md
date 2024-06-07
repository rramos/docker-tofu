# README.md

Example repo with OpenTofu code to install a docker image. 
This is a simple example just to validate the syntax and procedure

# Build the docker image

docker build -t pure_image:latest .

# Run tofu

cd tofu
tofu init
tofu apply
