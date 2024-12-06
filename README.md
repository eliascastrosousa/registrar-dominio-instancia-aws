# Registrando dominio na instancia aws

> Passo a passo para alterar o ip da instancia para um endereço fixo e apontar um dominio para o servidor.

### Adicionando IPv4 fixo para a Instancia

No painel do EC2 em Recursos ou na barra lateral em Rede e segurança, vá em IPs elásticos

![Recursos](https://github.com/user-attachments/assets/970a6b32-30a3-4262-b1c9-5d8f2fc047d4)

![Rede e segurança](https://github.com/user-attachments/assets/22f19263-5d55-4921-b63b-94795402d17c)

Vá em Alocar endereço IP elástico

![alocar ip elastico](https://github.com/user-attachments/assets/b2baf9ad-5b95-4bdc-9c3e-32082468dfe2)

Nenhuma alteração deverá ser feita na pagina a seguir, clique em alocar.

![alocação](https://github.com/user-attachments/assets/56400b1b-51e0-45c7-ae12-339f204833af)

Após isso, será criado um novo endereço de ip fixo na sua aba, ao lado do name "-" da nova instancia, aparecerá um icone para editar, você pode renomea-lo para melhor organização.
Marque o box do novo ip criado e em Ações, vá em Associar endereço IP elástico.

![Associar endereço de IP](https://github.com/user-attachments/assets/a9545697-bd6a-4b28-ad95-2e55932e01b1)

Em Tipo de recurso, escolhe a opção **Instancia**
Aparecerá logo abaixo a opção Instancia, vá nela e escolha a Instancia desejada a associar.
em Endereço IP privado, escolhe a opção desejada, se isto não tiver sido personalizado durante a criação da instancia, aparecerá apenas uma. marque ela. 

Feito isso, clique em Associar.

![image](https://github.com/user-attachments/assets/e3be1bb4-4f64-4f30-8cf0-1551be2f2b09)

Após isso, deverá aparecer a informação que o Endereço IP elástico foi associado com êxito.
Você pode verificar a associação retornando ao painel de instancias e verificando a alteração do ip da maquina ao novo que foi gerado. 

### Registrando dominio na Instancia.

