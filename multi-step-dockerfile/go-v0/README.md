### Build command
```bash
go build -o ./out/myapp
```

### Run Command 
```bash
./out/myapp
```
### Docker single stage build and run
```bash
docker build -t go-v0-app . -f Dockerfile.single
docker run --rm -d -p 8080:8080 go-v0-app
```
### Docker multi stage build and run
```bash
docker build -t go-v1-app . -f Dockerfile.multi
docker run --rm -d -p 8080:8080 go-v1-app
```
