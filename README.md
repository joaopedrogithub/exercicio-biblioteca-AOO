//exercicio-biblioteca-AOO
//classe pessoa 
//João Pedro Silvestre de Aragão 
public abstract class Pessoa{
public String nome;
public Pessoa (String nome){
this.nome = nome
}
public String getnome(){
return nome
}
public void setnome (String nome){
this.nome = nome;
}
//classes Autor,Professor e Aluno
public class Aluno extends Pessoa {
public Aluno(String nome){
        super(nome);
}
public int codigo{
this.codigo = codigo;
}
public String getNome() {
return this.nome;
}

 public void setNome(String nome) {
this.nome = nome;
}

 public int getcodigo() {
 return this.codigo;
 }

 public void setcodigo(int codigo) {
this.codigo=codigo;
}
}
public class Professor extends Pessoa{
public Professor(String nome){
super (nome);
public int codigo{
this.codigo = codigo;
}
public String getNome() {
return this.nome;
}

 public void setNome(String nome) {
this.nome = nome;
}

 public int getcodigo() {
 return this.codigo;
 }

 public void setcodigo(int codigo) {
this.codigo=codigo;
}
public class Autor{
public String nacionalidade;
this.nacionalidade=nacionalidade
public String getnacionalidade(){
return this.nacionalidade
}
public void setnacionalidade (String nacionalidade){
this.nacionalidade=nacionalidade
}

 



 






