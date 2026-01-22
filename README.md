//# Meu-her-i-ninja-Helmut
//Desafio do curso de lógica da DIO
class heroiDaAventura {
    constructor(nomeDoHeroi, idadeDoHeroi, tipoDoHeroi, alfaEOmega, tipoDeArmaOuMeio) {
        this.nomeDoHeroi = nomeDoHeroi;
        this.idadeDoHeroi = idadeDoHeroi;
        this.tipoDoHeroi = tipoDoHeroi;
        this.alfaEOmega = alfaEOmega;
        this.tipoDeArmaOuMeio = tipoDeArmaOuMeio;
    }
    
    profetizar() {
        console.log(`O herói chamado ${this.nomeDoHeroi} cuja idade é de ${this.idadeDoHeroi} anos, sendo do tipo ${this.tipoDoHeroi} é arrochado demais, vai derrotar monstros e vai encontrar o tesouro, se ele invocar o nome poderoso de ${this.alfaEOmega}!`);
    }

    atacar() {
        console.log(`O ${this.tipoDoHeroi} atacou usando um/a ${this.tipoDeArmaOuMeio}`);
        if (this.tipoDoHeroi === "mago") {
            console.log(`usou ${this.tipoDeArmaOuMeio}`)
        } else if (this.tipoDoHeroi === "guerreiro") {
            console.log(`usou ${this.tipoDeArmaOuMeio}`)
        } else if (this.tipoDoHeroi === "ninja") {
            console.log(`usou ${this.tipoDeArmaOuMeio}`)
        } else if (this.tipoDoHeroi === "monge") {
            console.log(`usou ${this.tipoDeArmaOuMeio}`)
        }
    }
}

let heroiDoBagulho = new heroiDaAventura("Helmut", 48, "ninja", "Yeshua Hamashia", "estilingue");

heroiDoBagulho.profetizar(); // O herói chamado Helmut cuja idade é de 48 anos, sendo do tipo ninja é arrochado demais, vai derrotar monstros e vai encontrar o tesouro, se ele invocar o nome poderoso de Yeshua Hamashia!

heroiDoBagulho.atacar(); // O ninja atacou usando um/a estilingue
//usou estilingue
