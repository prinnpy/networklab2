# TCP - Server/Client

- Upload both server folder and client folder to csegrid

### Server side (Run this first)

- cd into server folder then type: make 
- To run server: `./server`

```
make
./server
```

### Client side (Run this second)

- cd into client folder then type: make
- To run client: `./client csci-gnode-01` <- The number "01" varies depending on your server terminal number. This is just a sample case where your server runs on @csci-gnode-01:~/server
  
```
make
./client csci-gnode-01
```

### Run program (on client side)

##### Show files at the client’s current directory: `ls`
```
For command options type: 'help'
> ls
```

##### Display of current directory of the client: `pwd`
```
For command options type: 'help'
> pwd
```

##### Display current directory of the server: `spwd`
```
For command options type: 'help'
> spwd
```

##### Show files at the server’s current directory: `catalog`
```
For command options type: 'help'
> catalog
```

##### Download files: `download`
- DemoServer.txt and DemoClient.txt are included in its folder
```
For command options type: 'help'
> download

Enter download source filename:
> [Source filename (locates in server)]

Enter download destination filename:
> [Destination filename (new file name to save in client)]
```

##### Upload files: `upload`
- DemoServer.txt and DemoClient.txt are included in its folder
```
For command options type: 'help'
> upload

Enter upload source filename:
> [Source filename (locates in client)]

Enter upload destination filename:
> [Destination filename (new file name to save in server)]
```

##### Print all available commands: `help`
```
For command options type: 'help'
> help
```

##### Disconnect from server: `bye`
```
For command options type: 'help'
> bye
```

### Status

- 100% working locally and on csegrid!


---


**Name:** Prinn Prinyanut

**Instagram:** [@prinnpyn](https://www.instagram.com/prinnpyn)

**Email:** prinnprinyanut@gmail.com or prinn.prinyanut@ucdenver.edu

