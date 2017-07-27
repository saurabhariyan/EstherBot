# Resume bot based on heroku and Smooch

The bot is inspired by the EstherBot and aims to showcase my work. 

The logs for future comaprision is dumped here : 

        heroku logs -a your-app

        2016-05-09T14:08:34.966358+00:00 heroku[slug-compiler]: Slug compilation started
        2016-05-09T14:08:34.966363+00:00 heroku[slug-compiler]: Slug compilation finished
        2016-05-09T14:08:34.946344+00:00 heroku[web.1]: State changed from up to starting
        2016-05-09T14:08:34.945605+00:00 heroku[web.1]: Restarting
        2016-05-09T14:08:37.860802+00:00 heroku[web.1]: Stopping all processes with SIGTERM
        2016-05-09T14:08:39.493078+00:00 heroku[web.1]: Process exited with status 143
        2016-05-09T14:08:41.182450+00:00 heroku[web.1]: Starting process with command `npm start`
        2016-05-09T14:08:45.818995+00:00 app[web.1]:
        2016-05-09T14:08:45.819017+00:00 app[web.1]: > smooch-bot-example@1.0.0 start /app
        2016-05-09T14:08:45.819018+00:00 app[web.1]: > node heroku
        2016-05-09T14:08:45.819019+00:00 app[web.1]:
        2016-05-09T14:08:46.601444+00:00 app[web.1]: module.js:433
        2016-05-09T14:08:46.601454+00:00 app[web.1]:     throw err;
        2016-05-09T14:08:46.601455+00:00 app[web.1]:     ^
        2016-05-09T14:08:46.601456+00:00 app[web.1]:
        2016-05-09T14:08:46.601457+00:00 app[web.1]: SyntaxError: /app/script.json: Unexpected token }
        2016-05-09T14:08:46.601458+00:00 app[web.1]:     at Object.parse (native)
        2016-05-09T14:08:46.601458+00:00 app[web.1]:     at Object.Module._extensions..json (module.js:430:27)
        2016-05-09T14:08:46.601459+00:00 app[web.1]:     at Module.load (module.js:357:32)
        2016-05-09T14:08:46.601460+00:00 app[web.1]:     at Function.Module._load (module.js:314:12)
        2016-05-09T14:08:46.601460+00:00 app[web.1]:     at Module.require (module.js:367:17)
        2016-05-09T14:08:46.601461+00:00 app[web.1]:     at require (internal/module.js:20:19)
        2016-05-09T14:08:46.601462+00:00 app[web.1]:     at Object.<anonymous> (/app/script.js:6:21)
        2016-05-09T14:08:46.601473+00:00 app[web.1]:     at Module._compile (module.js:413:34)
        2016-05-09T14:08:46.601474+00:00 app[web.1]:     at Object.Module._extensions..js (module.js:422:10)
        2016-05-09T14:08:46.601474+00:00 app[web.1]:     at Module.load (module.js:357:32)


