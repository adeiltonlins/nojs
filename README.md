# nojs
app.post('/', (req, res) => {
    //pegando os dados da requisição do postman
    const nome = req.body.nome;
    const instag = req.body.instag;
    return res.json([nome, instag]);
  });

app.listen(8080,() =>{
    console.log("Servidor funcionando ") //o que aparece no terminal
})
