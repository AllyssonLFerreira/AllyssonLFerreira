app.get(`/Allysson/:Eu curto?`, (req, res)=>{
        let {Eu curto} = req.params
        res.send([Livros, Games, Violão, Gastronomia])
    })
    
    /* Sou incansavel quando o assunto é aprendizado! */
