
Array:
```go
var nums [5]int = [5]int{1,2,3,4,5}
```

Slice:
```go
nums := []int{1,2,3,4,5}

// Adicionar elementos
nums = append(nums, 0)
```

maps:
```go
idades := map[string]int {
	"Pedro": 22,
	"Elainne": 31
}
fmt.Println(idades["Pedro"])

idades["Fabiana"] = 45
```

Structs:
```go
type Pessoa struct {
	Nome string
	Idade int
}

p := Pessoa{
	Nome: "Pedro",
	Idade: 22
}

fmt.Println(p.Nome)
```
