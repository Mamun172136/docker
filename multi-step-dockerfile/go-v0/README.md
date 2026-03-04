### Build command
```bash
go build -o ./out/myapp
```

### Run Command 
```bash
./out/myapp
```
### Docker single stag build and run
```bash
docker build -t go-v0-app . -f Dockerfile.single
docker run --rm -d -p 8080:8080 go-v0-app
```
