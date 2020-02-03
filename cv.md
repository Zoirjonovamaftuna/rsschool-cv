# Hello World 

1. Maftuna Zoirjonova 
2. Contact Info: telegram (`@maftunz`), e-mail (`zoirjonovamaftuna@gmail.com`), instagram (`maftunz`) 
3. I want to become a software engeneer, wish to explore the IT world, learning something new during my work and career,
being creative and solving real problems with my programming skills are important things for me (life-long-learning) and as a Junior developer I am ready to learn new things from everywhere 
4. Skills: JavaScript es6, Angular 8, Node.js, express.js, BEM-methodologies, version control - git, a bit of python, websockets, herokuapp, mongoDB 
5. Code examples:
```
router.post("/users", async(req, res) => {
    const user = new User(req.body);
    try {
        await user.save();
        sendWelcomeEmail(user.email, user.name)
        const token = await user.generateAuthToken();
        res.status(201).send({
            user,
            token
        });
    } catch (e) {
        res.status(400).send(e);
    }
});
```
6. Experience: chat-app (https://mz-chat-app.herokuapp.com/), weather-app (https://mz-weather.herokuapp.com/) 7. Education : the-complete-nodejs-developer-course-3
in udemy, lectures in the base learning center(front-end development course), codecademy, codewars, htmlacademy) 8. English : IELTS 6.5 certificate
