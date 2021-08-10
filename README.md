# save-and-load

# Stop Container
```
docker stop [container]
```

# Save Container as Image
```
docker commit [Container ID] [Image Name]
```
tip!) use  ```docker ps -a``` to find Container ID

# Save Image as File
```
docker save [Image Name] > [File Path & File Name]
```

# Load File to Image
```
sudo load [File Path & File Name]
```
