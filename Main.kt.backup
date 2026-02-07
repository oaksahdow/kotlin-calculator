fun main() {
    var continuar = true
    
    while (continuar) {
        println("\n=== CALCULADORA KOTLIN ===")
        
        println("\nPrimeiro número: ")
        val num1 = readLine()?.toDoubleOrNull() ?: 0.0

        println("Segundo número: ")
        val num2 = readLine()?.toDoubleOrNull() ?: 0.0

        println("\n=== OPERAÇÕES ===")
        println("1 - Soma (+)")
        println("2 - Subtração (-)")
        println("3 - Multiplicação (*)")
        println("4 - Divisão (/)")
        print("Escolha (1-4): ")

        when (readLine()?.toIntOrNull()) {
            1 -> println("\n✅ Resultado: ${num1 + num2}")
            2 -> println("\n✅ Resultado: ${num1 - num2}")
            3 -> println("\n✅ Resultado: ${num1 * num2}")
            4 -> {
                if (num2 != 0.0) {
                    println("\n✅ Resultado: ${num1 / num2}")
                } else {
                    println("\n❌ ERRO: Não é possível dividir por zero!")
                }
            }
            else -> println("\n⚠️ Opção inválida! Escolha de 1 a 4.")
        }

        println("\n✨ Feito com Kotlin no GitHub Codespaces! ✨")
        
        print("\n📝 Calcular novamente? (s/n): ")
        continuar = readLine()?.lowercase() == "s"
    }
    println("\n👋 Até logo!")
}