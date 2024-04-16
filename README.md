# desafio_nivel_de_heroi
aula de logica d programação , código formatado para selecionar classe de jogador apartir da experiência dele 


class Personagem {
    constructor(nome, xp) {
      this.nome = nome;
      this.xp = xp;
      this.classe = this.definirClasse();
    }
  
    definirClasse() {
      if (this.xp >= 0 && this.xp < 1000) {
        return "Ferro";
      } else if (this.xp >= 1001 && this.xp < 2000) {
        return "Bronze";
      } else if (this.xp >= 2001 && this.xp < 5000) {
        return "Prata";
      } else if (this.xp >= 5001 && this.xp < 7000)  {
        return "Ouro";
      } else if (this.xp >= 7001 && this.xp < 8000)   {
        return "Platina";
      } else if (this.xp >= 8001 && this.xp < 9000)   {
        return "Ascendente";
      } else if (this.xp >= 9001 && this.xp < 10000)    {
        return "Imortal";
      } else if (this.xp >= 10001)                   {
        return "Radiante";
      }
    }
  }
  

  

