### A command line UI to manage AWS Session Manager sessions

![alt text](image.png)

#### Install
```bash
pip install aws-session-manager
```

#### Configure
Create configuration file from example `aws_session_manager\example.config.yaml`.

#### Run
```bash
python -m aws_session_manager your_config.yaml
```

#### How to use
Press keys `1-9` to establish a connection.  
Press `c` to open the application of choice for the connection (as configured in the yaml file).  
Press keys `1-9` again to close a connection.  
`l` shows logs.  
`x` to exit.  
