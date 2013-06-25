# Angular Express Starter
Just some quick scaffolding to set up a __dev__ environment for Angular. Based on [Angular Express Seed](https://github.com/btford/angular-express-seed), but tries not to change the orginal [Angular Seed](https://github.com/angular/angular-seed).

The intent of this project isn't to try to be a one size fits all production seed environment. Instead this is just a wrapper to the original angular seed project. Some of the files in the scripts folder are no longer needed like `scripts/webserver.js`, but I wanted to keep the original seed intact.

The entire angular seed project is included as a submodule. This is valuable because we can use the included testing harness from the beginning. Additionally we can write our templates in pure html which saves us from another layer of abstraction.

That said, if you'd like to see the structure of a more production ready app check out Brain Ford's excellent [Angular Express Seed](https://github.com/btford/angular-express-seed). In fact, check out his blog post in any case for the best simple explanation of a simple CRUD app.

## Why
Using the Angular Seed Project is great to get your feet wet, but ery quickly you'll need a way to persist data on the server.

Finally, don't feel like you are tried to Node for your production env. If you are consistent with your api, you should be able to drop in you app that you developed here into your flask/sinatra/rails/django backend. This way we maintain the separation between frontend and backend development.
## Initial Config
	$ git clone <repo_name>
	$ git submodule init
	$ git submodule update

Now you have all the code to get stated. Next install the node dependencies (express + ejs):
	$ cd angular-express-starter
	$ npm install

Finally serve up the app:
	$ node app.js

Head over to [http://localhost:3000/app/index.html](http://localhost:3000/app/index.html)

## License

The MIT License (MIT)

Copyright (c) 2013 Andrew Jesaitis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


