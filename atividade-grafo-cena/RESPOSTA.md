ATIVIDADE 02 - BRAÇO ROBÓTICO

Disciplina: Computação Gráfica
Aluno: João Pedro de Oliveira Cruz

Foi necessário utilizar objetos `Object3D` como pivôs porque as caixas são criadas centralizadas na origem local, e girá-las diretamente faria com que a rotação ocorresse em torno de seus próprios centros. Com os pivôs, foi possível posicionar as articulações nas extremidades das peças e organizar os objetos em um grafo de cena. Dessa forma, a rotação da base movimenta todo o braço, enquanto a rotação do ombro e do cotovelo movimenta as respectivas partes conectadas, mantendo a hierarquia e a articulação do robô.