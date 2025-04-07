## This a static site made using Hugo and pulumi static-website-template

### To run it locally and make changes:-
- make sure you hugo installed 
- Run these commands from root directory
```
cd Mysite && hugo server 
```
- after the changes build the site 
```
hugo
```

### To deploy this site to aws
make sure you have pulumi and aws cli installed on your system. To  install pulumi cli  [pulumi cli](https://www.pulumi.com/docs/iac/cli/)
- configure your aws credentials by running `aws configure`.
- Run ```pulumi up ``` from root do deploy your local stack and enjoy.
