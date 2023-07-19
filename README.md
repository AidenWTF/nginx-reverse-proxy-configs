# Nginx Reverse Proxy Configs by Aiden


Welcome to the Nginx Reverse Proxy Configurations repository! Here, you'll find a collection of tested Nginx configuration files for setting up reverse proxies-


## How to Use

1. Clone this repository to your local machine using the following command:
```
git clone https://github.com/AidenWTF/nginx-reverse-proxy-configs.git
```
2. Find the specific configurations you need.

3. Customize the configuration files according to your specific requirements. Make sure to update server names, backend server addresses, ports, and any other relevant settings.

4. Copy the desired configuration file(s) to your Nginx configuration directory. The default locations for Nginx configuration files are:
  - Ubuntu/Debian: `/etc/nginx/sites-available/`
  - CentOS/RHEL: `/etc/nginx/conf.d/`
  - Custom installation: Check the `nginx.conf` file for the `include` directive that includes other configuration files.


5. Create symbolic links to the `sites-enabled` directory to enable the configurations. On Ubuntu/Debian, you can use the following command:
```
sudo ln -s /etc/nginx/sites-available/your_config_file.conf /etc/nginx/sites-enabled/
```
6. Test the Nginx configuration for syntax errors using the following command:
```
sudo nginx -t
```
7. If the test is successful, reload Nginx to apply the changes:
```
sudo nginx -s reload
```


## Contributions

I value contributions from the open-source community! If you have a specific Nginx reverse proxy configuration that you believe would benefit others or you notice something wrong, please feel free to submit a pull request. Together, we can improve the collection.



For any questions or support, please feel free to open an issue in the repository.
Happy proxying! 😊



### You made it so far, heres a joke
 ![Jokes Card](https://readme-jokes.vercel.app/api)
