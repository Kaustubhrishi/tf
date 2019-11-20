provider "aws" {
  region     = "eu-west-2"
}

resource "aws_instance" "rhel-8" {
  ami           = "ami-0a0cb6c7bcb2e4c51"
  instance_type = "t2.micro"
  
  tags = {
    Name = "HelloWorld"
    Cost_Center = "c1"
  }
  
}
