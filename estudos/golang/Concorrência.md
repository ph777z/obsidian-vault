
## Goroutines

Goroutines são funções que são executadas em paralelo:

```go
func digaOla() {
	fmt.Println("Olá!")
}

func main() {
	go digaOla()
	fmt.Println("Mundo")

	time.Sleep(1 * time.Second)
}
```

## Canais

Comunicação entre goroutines:
```go
func digaOla(canal chan string) {
	canal <- "Olá do canal!"
}

func main() {
	canal := make(chan string)
	go digaOla(canal)
	mensagem := <-canal
	fmt.Println(mensagem)
}
```
