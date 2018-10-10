# To run the project 

1. Clone the project 
2. Install ansible 
3. Run `ansbile-playbook nginx.yml`
4. Open browser and enter `localhost:8082`

## Please note

That on my local environment port 80 was busy ,by anothe app, so i have to change it to port 8082 (hope that you wouldn't count that as a mistake ). However that value could be adjusted inside nginx.yml playbook 

```   host_port: 8082 ```

