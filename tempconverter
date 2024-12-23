package main

import (
	"fmt"
)

func main() {
	var temp float64
	var escala string

	fmt.Println("Digite o valor da temperatura seguido da escala (C, F, ou K):")
	fmt.Scanf("%f%s", &temp, &escala)

	switch escala {
	case "C", "c":
		fmt.Printf("Temperatura em Celsius: %.2f°C\n", temp)
		fmt.Printf("Convertida para Fahrenheit: %.2f°F\n", (temp*9/5)+32)
		fmt.Printf("Convertida para Kelvin: %.2fK\n", temp+273.15)
	case "F", "f":
		fmt.Printf("Temperatura em Fahrenheit: %.2f°F\n", temp)
		fmt.Printf("Convertida para Celsius: %.2f°C\n", (temp-32)*5/9)
		fmt.Printf("Convertida para Kelvin: %.2fK\n", ((temp-32)*5/9)+273.15)
	case "K", "k":
		fmt.Printf("Temperatura em Kelvin: %.2fK\n", temp)
		fmt.Printf("Convertida para Celsius: %.2f°C\n", temp-273.15)
		fmt.Printf("Convertida para Fahrenheit: %.2f°F\n", (temp-273.15)*9/5+32)
	default:
		fmt.Println("Escala inválida. Use C para Celsius, F para Fahrenheit ou K para Kelvin.")
	}
}
