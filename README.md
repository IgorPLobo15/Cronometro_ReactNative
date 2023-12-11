# Documentação do Código - Cronômetro em React Native

## Introdução

O código fornecido implementa um aplicativo de cronômetro simples em React Native. O cronômetro possui funcionalidades básicas, como iniciar, parar, limpar e exibir o último tempo registrado.

## Estrutura do Código

### Variáveis de Estado
1. **numero**: Armazena o tempo atual formatado no formato HH:mm:ss.
2. **botao**: Armazena o texto do botão, que alterna entre 'INICIAR' e 'PARAR' com base no estado do cronômetro.
3. **ultimo**: Armazena o último tempo registrado quando o botão "LIMPAR" é pressionado.

### Variáveis de Controle do Tempo
1. **timer**: Controla o intervalo de atualização do cronômetro.
2. **ss, mm, hh**: Armazenam os valores de segundos, minutos e horas do cronômetro.

### Funções Principais
1. **vai()**: Inicia ou para o cronômetro com base no estado atual. Atualiza o estado a cada segundo.
2. **limpar()**: Para o cronômetro e reinicia todas as variáveis relacionadas ao tempo. Armazena o último tempo registrado.

## Componentes React Native Utilizados
1. **View**: Componente contêiner principal.
2. **Text**: Exibe o tempo atual do cronômetro e mensagens adicionais.
3. **Image**: Exibe uma imagem de um cronômetro.
4. **TouchableOpacity**: Botões que respondem ao toque do usuário.

## Estilos (StyleSheet)
- **container**: Estilo do contêiner principal.
- **timer**: Estilo do texto que exibe o tempo do cronômetro.
- **btnArea**: Estilo da área que contém os botões.
- **btn**: Estilo dos botões de controle (INICIAR/PARAR e LIMPAR).
- **areaUltima**: Estilo da área que exibe o último tempo registrado.
- **textoCorrida**: Estilo do texto que exibe o último tempo registrado.

## Uso do Aplicativo
- Ao iniciar o aplicativo, um cronômetro e dois botões são exibidos.
- O botão principal alterna entre "INICIAR" e "PARAR" conforme o cronômetro é controlado.
- O botão "LIMPAR" reinicia o cronômetro e exibe o último tempo registrado.
- O último tempo registrado é exibido abaixo dos botões.

## Considerações Finais
O código fornece uma implementação básica de um cronômetro em React Native. A estrutura modular e os componentes utilizados facilitam a compreensão e modificação do código para atender a requisitos específicos.
