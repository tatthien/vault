```go

cmd := exec.Command("echo", "Golang is awesome")

cmd.Stdout = os.Stdout

if err := cmd.Run(); err != nil {
	log.Fatal(err)
}
```