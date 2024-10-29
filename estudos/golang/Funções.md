
Definição de função:
```go
func saudacao(nome string) string {
	return "Olá, " + nome
}
```

Chamada de função:
```go
func main() {
	mensagem := saudacao("Pedro")
	fmt.Println(mensagem)
}
```

Funções com múltiplos retornos:
```go
func dividir(a, b float64) (float64, error) {
	if b == 0 {
		return 0, fmt.Error("divisão por zero")
	}
	return a / b, nil
}
```

Funções Anônimas:
```go
multiplicacao := func(x int) int {
	return x * x
}

resultado := multiplicacao(5)
fmt.Println(resultado)
```

#go #funções