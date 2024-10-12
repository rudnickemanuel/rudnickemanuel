- 👋 Hi, I’m @rudnickemanuel

#include <iostream>
  using namespace std;
  int main() {
    int i, cep1;
        i = 0;
     cout << "OBS: Apenas para relembrar que, todas as encomendas tem a opção de envio via Correios. Entretanto, nem todas as encomendas possuem entrega domiciliar!";
    cout << "\n";
    cout << "\n";
    cout << "Algumas encomendas possuem restrição de entrega, dado por não ser acessível ou então, local de perigo (assaltos).";
    cout << "\n";
    cout << "\n";
    cout << "Para isso, sugiro que pesquise o CEP da encomenda via Correios no link abaixo. Agradeço a compreensão! <3";
    cout << "\n";
    cout << "\nhttps://www2.correios.com.br/sistemas/precosprazos/restricaoentrega/";

    cout << "\n";
    cout << "\n";
    cout << "\n";
    cout << "Transportadora registradas: \n\n1. R3 SP";
    cout << "\n2. R3 RJ";
    cout << "\n3. FOXEXPRESS";
    cout << "\n4. GD Florianópolis";

    while (i < 1000) {
      cout << "\n\n\nDigite o CEP: ";
      cin >> cep1;
      cout << "\n";

      if (cep1 >= 01000001 && cep1 < 10000000) {
        cout << "Essa encomenda tem a opção de ser enviada via Correios ou via transportadora";
        cout << "\n";
        cout << "Caso a escolha seja transportadora, a responsável será a R3 SP.";
      }

      else if (cep1 >= 20000001 && cep1 <= 26599999) {
        cout << "Essa encomenda tem a opção de ser enviada via Correios ou via transportadora.";
        cout << "\n";
        cout << "Caso a escolha seja transportadora, a responsável será a R3 RJ.";
      }

        else if (cep1 >= 80000001 && cep1 <= 83419999){
          cout << "Essa encomenda possui a opção de ser enviada via Correios ou via transportadora.";
          cout << "\n";
          cout << "Caso a escolha seja transportadora, a responsável, será FOXEXPRESS.";
        }

        else if (cep1 >= 88000001 && cep1 <= 88489999){
          cout << "Essa encomenda possui a opção de ser enviada via Correios ou via transportadora.";
          cout << "\n";
          cout << "Caso a escolha seja transportadora, a responsável será a GD Florianópolis.";
        }

      else {
        cout << "Esse CEP não atende a nenhuma transportadora que possuímos em nosso banco de dados. Pedimos para que verifique se a mesma não será via Correios ou outra transportadora.";
        cout << "\n\nSegue link para verificar a localidade do CEP informado: https://buscacepinter.correios.com.br/app/endereco/index.php ";
}
}
}

<!---
rudnickemanuel/rudnickemanuel is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
