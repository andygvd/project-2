const express = require('express')
const app = express()
const port = 3000
const path = require('path')


app.get('/',(req,res) =>{
    res.sendFile(path.join(__dirname,'./public','index.html'))
})
app.get('/andy',(req,res) =>{
    res.sendFile(path.join(__dirname,'./public','Andy.html'))
})
app.use(express.json());
app.use(express.urlencoded({ extended: true }));
app.post('/comment', function (req, res) {
    console.log(req.body);
    res.send();
});

app.listen(port, () => {
    console.log(`Example app listening on port ${port}`)
  })

