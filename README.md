# prova-atitudinal-pdm-danilo-erick

let aluno1 = {
    nome : "Danilo",
    idade : 17,
    cursando : ["JS", "PYTHON", "BD2",]
    presença : ["2024-01-10", "2024-01-12"],
    ra : 2256871,
}

let aluno2 = {
    nome : "Erick",
    idade : 13,
    cursando : ["BD1", "PDM",]
    presença : ["2024-01-21", "2024-01-22"],
    ra : 2265843,
}

function ValidaCadastro(){
    
    if(aluno.nome >= 10) {
        if(aluno.idade >= 14){
            if(aluno.cursando.length >= 3) {
                if(aluno.presença.length >= 2){
                    if(aluno.ra.length == 7){
                        console.log("Cadastro concluido com sucesso")
                    } else {
                        console.log("Erro: O RA do aluno deve contar no minimo 7 caracteres")
                        console.log("Erro: A idade do aluno deve ser superior a 14 anos")
                        console.log("Erro: O aluno deve cursar no minimo 3 materias")
                        console.log("Erro: O aluno deve conter no minimo 2 dias de presença")
                        console.log("Erro: O nome do aluno deve conter no minimo 10 caracteres")

                    }

                    }
                }
    
        }
}

DANILO NUNES FERNANDES
ERICK HENRIQUE DALBEN
