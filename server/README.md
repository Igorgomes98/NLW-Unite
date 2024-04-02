# pass.in

O pass.in é uma aplicação de **gestão de participantes em eventos presenciais**

A ferramenta permite que o orfaniz\ador cadastre um evento e avra uma página pública de inscrição.

Os participantes inscritos podem emitir uma credencial para check-in no dia do evento.

O sistema fará um scan da credencial do participante para permitire a entrada no evento

## Requisitos

### Requisitos Funcionais

- [ ] O organizador deve poder cadastrar um novo evento;
- [ ] O organizador deve poder visualizar dados de um evento;
- [ ] O organizador deve poder visualizar a lista de participantes;
- [ ] O participante deve poder se inscrever em um evento;
- [ ] O participante deve poder visualizar seu crachá de inscrição;
- [ ] O participante deve poder realizar check-in no evento;

### Regras de negócio

- [ ] O participante só pode se inscrever em um evento uma única vez;
- [ ] O participante só pode se inscrever em eventos com vagas disponiveis;
- [ ] O participante só pode realizar check-in em um evento uma única vez;

### Requisitos Não-Funcionais

- [ ] O check-in no evento será realizado através de um QRCode;