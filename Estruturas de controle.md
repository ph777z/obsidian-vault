
Condicionais:
```go
if idade >= 18 {
	fmt.Println("Adulto")
} else if idade >= 12 {
	fmt.Println("Adolescente")
} else {
	fmt.Println("Menor de idade")
}
```

Switch:
```go
dia := "sexta"
switch dia {
	case "sexta":
		fmt.Println("Sextou!")
	case "segunda":
		fmt.Println("tristou!")
	default:
		fmt.Println("só vai")
}
```

## Laços

for:
```go
for i := 0; i < 10; i++ {
	fmt.Println(i)
}
```

while:
```go
i := 0
for i < 10 {
	fmt.Println(i)
	i++
}
```

iteração sobre slices ou arrays:
```go
nums := []int{2,3,4,5}
for index, value := range nums {
	fmt.Println(index, value)
}
```