# api documentation for  [osmosis (v1.1.4)](https://github.com/rchipka/node-osmosis#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-osmosis.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-osmosis) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-osmosis.svg)](https://travis-ci.org/npmdoc/node-npmdoc-osmosis)
#### Web scraper for NodeJS

[![NPM](https://nodei.co/npm/osmosis.png?downloads=true)](https://www.npmjs.com/package/osmosis)

[![apidoc](https://npmdoc.github.io/node-npmdoc-osmosis/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-osmosis_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-osmosis/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-osmosis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-osmosis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "rchipka",
        "email": "chipka01@email.franklin.edu"
    },
    "bugs": {
        "url": "https://github.com/rchipka/node-osmosis/issues"
    },
    "dependencies": {
        "libxmljs-dom": "0.0.8",
        "needle": "1.3.0"
    },
    "description": "Web scraper for NodeJS",
    "devDependencies": {
        "jscs": ">=3.0.2",
        "nodeunit": "0.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "36b773b6c63b65d70f186b9cf44da3e5d67a2b1b",
        "tarball": "https://registry.npmjs.org/osmosis/-/osmosis-1.1.4.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "7c20daa42aec9b994c5661289774c6da18e367a1",
    "homepage": "https://github.com/rchipka/node-osmosis#readme",
    "keywords": [
        "web",
        "scraper",
        "crawler",
        "html",
        "xml",
        "dom",
        "parser"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "rchipka",
            "email": "chipka01@email.franklin.edu"
        }
    ],
    "name": "osmosis",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rchipka/node-osmosis.git"
    },
    "scripts": {
        "test": "node ./node_modules/.bin/nodeunit test"
    },
    "version": "1.1.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module osmosis](#apidoc.module.osmosis)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>Command (parent)](#apidoc.element.osmosis.Command)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>Data (parent)](#apidoc.element.osmosis.Data)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>Queue (instance)](#apidoc.element.osmosis.Queue)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>click (arg1, arg2, arg3)](#apidoc.element.osmosis.click)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>config (option, value)](#apidoc.element.osmosis.config)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>contains (arg1, arg2, arg3)](#apidoc.element.osmosis.contains)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>cookie (arg1, arg2, arg3)](#apidoc.element.osmosis.cookie)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>data (arg1, arg2, arg3)](#apidoc.element.osmosis.data)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>debug (arg1, arg2, arg3)](#apidoc.element.osmosis.debug)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>delay (arg1, arg2, arg3)](#apidoc.element.osmosis.delay)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>do (arg1, arg2, arg3)](#apidoc.element.osmosis.do)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>document (arg1, arg2, arg3)](#apidoc.element.osmosis.document)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>done (arg1, arg2, arg3)](#apidoc.element.osmosis.done)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>else (arg1, arg2, arg3)](#apidoc.element.osmosis.else)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>end (arg1, arg2, arg3)](#apidoc.element.osmosis.end)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>error (arg1, arg2, arg3)](#apidoc.element.osmosis.error)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>fail (arg1, arg2, arg3)](#apidoc.element.osmosis.fail)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>filter (arg1, arg2, arg3)](#apidoc.element.osmosis.filter)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>find (arg1, arg2, arg3)](#apidoc.element.osmosis.find)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>findCommandArg (arg1, arg2, arg3)](#apidoc.element.osmosis.findCommandArg)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>follow (arg1, arg2, arg3)](#apidoc.element.osmosis.follow)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>get (arg1, arg2, arg3)](#apidoc.element.osmosis.get)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>getInstance (arg1, arg2, arg3)](#apidoc.element.osmosis.getInstance)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>getOpts (arg1, arg2, arg3)](#apidoc.element.osmosis.getOpts)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>header (arg1, arg2, arg3)](#apidoc.element.osmosis.header)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>headers (arg1, arg2, arg3)](#apidoc.element.osmosis.headers)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>if (arg1, arg2, arg3)](#apidoc.element.osmosis.if)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>inherit (arg1, arg2, arg3)](#apidoc.element.osmosis.inherit)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>isCommand (arg1, arg2, arg3)](#apidoc.element.osmosis.isCommand)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>learn (arg1, arg2, arg3)](#apidoc.element.osmosis.learn)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>log (arg1, arg2, arg3)](#apidoc.element.osmosis.log)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>login (arg1, arg2, arg3)](#apidoc.element.osmosis.login)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>match (arg1, arg2, arg3)](#apidoc.element.osmosis.match)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>paginate (arg1, arg2, arg3)](#apidoc.element.osmosis.paginate)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>parse (arg1, arg2, arg3)](#apidoc.element.osmosis.parse)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>pause (arg1, arg2, arg3)](#apidoc.element.osmosis.pause)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>post (arg1, arg2, arg3)](#apidoc.element.osmosis.post)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>proxy (arg1, arg2, arg3)](#apidoc.element.osmosis.proxy)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>request (arg1, arg2, arg3)](#apidoc.element.osmosis.request)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>resume (arg1, arg2, arg3)](#apidoc.element.osmosis.resume)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>rewrite (arg1, arg2, arg3)](#apidoc.element.osmosis.rewrite)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>run (arg1, arg2, arg3)](#apidoc.element.osmosis.run)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>select (arg1, arg2, arg3)](#apidoc.element.osmosis.select)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>set (arg1, arg2, arg3)](#apidoc.element.osmosis.set)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>setInstance (arg1, arg2, arg3)](#apidoc.element.osmosis.setInstance)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>setOpt (arg1, arg2, arg3)](#apidoc.element.osmosis.setOpt)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>start (arg1, arg2, arg3)](#apidoc.element.osmosis.start)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>stop (arg1, arg2, arg3)](#apidoc.element.osmosis.stop)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>submit (arg1, arg2, arg3)](#apidoc.element.osmosis.submit)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>success (arg1, arg2, arg3)](#apidoc.element.osmosis.success)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>then (arg1, arg2, arg3)](#apidoc.element.osmosis.then)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>train (arg1, arg2, arg3)](#apidoc.element.osmosis.train)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>trigger (arg1, arg2, arg3)](#apidoc.element.osmosis.trigger)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>use (arg1, arg2, arg3)](#apidoc.element.osmosis.use)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>using (arg1, arg2, arg3)](#apidoc.element.osmosis.using)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>window (arg1, arg2, arg3)](#apidoc.element.osmosis.window)
1.  object <span class="apidocSignatureSpan">osmosis.</span>Command.prototype
1.  object <span class="apidocSignatureSpan">osmosis.</span>Data.prototype
1.  object <span class="apidocSignatureSpan">osmosis.</span>Form
1.  object <span class="apidocSignatureSpan">osmosis.</span>Queue.prototype

#### [module osmosis.Command](#apidoc.module.osmosis.Command)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>Command (parent)](#apidoc.element.osmosis.Command.Command)

#### [module osmosis.Command.prototype](#apidoc.module.osmosis.Command.prototype)
1.  boolean <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>isCommand
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>click ()](#apidoc.element.osmosis.Command.prototype.click)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>config ()](#apidoc.element.osmosis.Command.prototype.config)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>contains ()](#apidoc.element.osmosis.Command.prototype.contains)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>cookie ()](#apidoc.element.osmosis.Command.prototype.cookie)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>data ()](#apidoc.element.osmosis.Command.prototype.data)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>debug (msg, prefixed)](#apidoc.element.osmosis.Command.prototype.debug)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>delay ()](#apidoc.element.osmosis.Command.prototype.delay)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>do ()](#apidoc.element.osmosis.Command.prototype.do)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>done ()](#apidoc.element.osmosis.Command.prototype.done)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>end (context, data)](#apidoc.element.osmosis.Command.prototype.end)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>error (msg, prefixed)](#apidoc.element.osmosis.Command.prototype.error)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>fail ()](#apidoc.element.osmosis.Command.prototype.fail)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>filter ()](#apidoc.element.osmosis.Command.prototype.filter)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>find ()](#apidoc.element.osmosis.Command.prototype.find)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>findCommandArg (obj)](#apidoc.element.osmosis.Command.prototype.findCommandArg)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>follow ()](#apidoc.element.osmosis.Command.prototype.follow)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>get ()](#apidoc.element.osmosis.Command.prototype.get)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>getInstance ()](#apidoc.element.osmosis.Command.prototype.getInstance)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>getOpts ()](#apidoc.element.osmosis.Command.prototype.getOpts)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>header ()](#apidoc.element.osmosis.Command.prototype.header)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>headers ()](#apidoc.element.osmosis.Command.prototype.headers)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>if ()](#apidoc.element.osmosis.Command.prototype.if)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>inherit (command)](#apidoc.element.osmosis.Command.prototype.inherit)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>learn ()](#apidoc.element.osmosis.Command.prototype.learn)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>log (msg, prefixed)](#apidoc.element.osmosis.Command.prototype.log)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>login ()](#apidoc.element.osmosis.Command.prototype.login)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>match ()](#apidoc.element.osmosis.Command.prototype.match)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>paginate ()](#apidoc.element.osmosis.Command.prototype.paginate)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>parse ()](#apidoc.element.osmosis.Command.prototype.parse)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>pause ()](#apidoc.element.osmosis.Command.prototype.pause)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>post ()](#apidoc.element.osmosis.Command.prototype.post)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>proxy ()](#apidoc.element.osmosis.Command.prototype.proxy)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>request (method, context, href, params, callback)](#apidoc.element.osmosis.Command.prototype.request)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>resume ()](#apidoc.element.osmosis.Command.prototype.resume)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>rewrite ()](#apidoc.element.osmosis.Command.prototype.rewrite)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>run (context, data)](#apidoc.element.osmosis.Command.prototype.run)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>select ()](#apidoc.element.osmosis.Command.prototype.select)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>set ()](#apidoc.element.osmosis.Command.prototype.set)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>setInstance (val)](#apidoc.element.osmosis.Command.prototype.setInstance)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>setOpt (name, value)](#apidoc.element.osmosis.Command.prototype.setOpt)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>start (context, data)](#apidoc.element.osmosis.Command.prototype.start)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>stop ()](#apidoc.element.osmosis.Command.prototype.stop)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>submit ()](#apidoc.element.osmosis.Command.prototype.submit)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>success ()](#apidoc.element.osmosis.Command.prototype.success)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>then ()](#apidoc.element.osmosis.Command.prototype.then)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>train ()](#apidoc.element.osmosis.Command.prototype.train)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>trigger ()](#apidoc.element.osmosis.Command.prototype.trigger)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>use ()](#apidoc.element.osmosis.Command.prototype.use)
1.  [function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>using ()](#apidoc.element.osmosis.Command.prototype.using)

#### [module osmosis.Data](#apidoc.module.osmosis.Data)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>Data (parent)](#apidoc.element.osmosis.Data.Data)

#### [module osmosis.Data.prototype](#apidoc.module.osmosis.Data.prototype)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>child ()](#apidoc.element.osmosis.Data.prototype.child)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>clone ()](#apidoc.element.osmosis.Data.prototype.clone)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>copy ()](#apidoc.element.osmosis.Data.prototype.copy)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>done (cb)](#apidoc.element.osmosis.Data.prototype.done)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>extend (object)](#apidoc.element.osmosis.Data.prototype.extend)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>getIndex ()](#apidoc.element.osmosis.Data.prototype.getIndex)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>getObject ()](#apidoc.element.osmosis.Data.prototype.getObject)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>isArray (val)](#apidoc.element.osmosis.Data.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>isEmpty ()](#apidoc.element.osmosis.Data.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>merge (child)](#apidoc.element.osmosis.Data.prototype.merge)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>next ()](#apidoc.element.osmosis.Data.prototype.next)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>push (val)](#apidoc.element.osmosis.Data.prototype.push)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>ref ()](#apidoc.element.osmosis.Data.prototype.ref)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>set (key, val)](#apidoc.element.osmosis.Data.prototype.set)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>setIndex (index)](#apidoc.element.osmosis.Data.prototype.setIndex)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>setObject (object)](#apidoc.element.osmosis.Data.prototype.setObject)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>toArray ()](#apidoc.element.osmosis.Data.prototype.toArray)
1.  [function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>unref ()](#apidoc.element.osmosis.Data.prototype.unref)

#### [module osmosis.Form](#apidoc.module.osmosis.Form)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>getAction (node)](#apidoc.element.osmosis.Form.getAction)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>getEnctype (node)](#apidoc.element.osmosis.Form.getEnctype)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>getForm (node)](#apidoc.element.osmosis.Form.getForm)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>getInputs (node)](#apidoc.element.osmosis.Form.getInputs)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>getMethod (node)](#apidoc.element.osmosis.Form.getMethod)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>getParams (node)](#apidoc.element.osmosis.Form.getParams)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>getSubmitButton (node)](#apidoc.element.osmosis.Form.getSubmitButton)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>isForm (node)](#apidoc.element.osmosis.Form.isForm)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>isMultipart (node)](#apidoc.element.osmosis.Form.isMultipart)
1.  [function <span class="apidocSignatureSpan">osmosis.Form.</span>submit ()](#apidoc.element.osmosis.Form.submit)

#### [module osmosis.Queue](#apidoc.module.osmosis.Queue)
1.  [function <span class="apidocSignatureSpan">osmosis.</span>Queue (instance)](#apidoc.element.osmosis.Queue.Queue)

#### [module osmosis.Queue.prototype](#apidoc.module.osmosis.Queue.prototype)
1.  [function <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>dequeue ()](#apidoc.element.osmosis.Queue.prototype.dequeue)
1.  [function <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>enqueue (object)](#apidoc.element.osmosis.Queue.prototype.enqueue)
1.  [function <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>pop ()](#apidoc.element.osmosis.Queue.prototype.pop)
1.  [function <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>push ()](#apidoc.element.osmosis.Queue.prototype.push)
1.  number <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>change
1.  number <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>count
1.  number <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>done
1.  number <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>length
1.  number <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>requests



# <a name="apidoc.module.osmosis"></a>[module osmosis](#apidoc.module.osmosis)

#### <a name="apidoc.element.osmosis.Command"></a>[function <span class="apidocSignatureSpan">osmosis.</span>Command (parent)](#apidoc.element.osmosis.Command)
- description and source-code
```javascript
function Command(parent) {
    var self = this;

    if (Object.getPrototypeOf(parent) === Command.prototype) {
        // parent is a Command
        this.prev = parent;
        Object.defineProperty(this, 'instance', {
            get: Command.prototype.getInstance,
            set: Command.prototype.setInstance
        });
    } else if (parent !== undefined) {
        // 'parent' is an Osmosis instance
        this.instance = parent;
        // Call 'process.nextTick' so other instances can initialize
        process.nextTick(function () {
            // Attempt to auto-run the instance only IF:
            //  * Not already running
            //  * Not created using 'new'
            //  * Not a child instance
            if (parent.calledWithNew !== true &&
                parent.parent === undefined) {
                process.nextTick(function () {
                    // Run on nextTick to allow any
                    // runtimeCommands to finish first
                    parent.run();
                });
            }
        });
    }

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Data"></a>[function <span class="apidocSignatureSpan">osmosis.</span>Data (parent)](#apidoc.element.osmosis.Data)
- description and source-code
```javascript
function Data(parent) {
    this.stack = { count: 0 };

    if (parent) {
        this.parent = parent;
    }

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Queue"></a>[function <span class="apidocSignatureSpan">osmosis.</span>Queue (instance)](#apidoc.element.osmosis.Queue)
- description and source-code
```javascript
function Queue(instance) {
    this.instance = instance;
    this.opts = instance.opts;
    this.queue = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.click"></a>[function <span class="apidocSignatureSpan">osmosis.</span>click (arg1, arg2, arg3)](#apidoc.element.osmosis.click)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.config"></a>[function <span class="apidocSignatureSpan">osmosis.</span>config (option, value)](#apidoc.element.osmosis.config)
- description and source-code
```javascript
config = function (option, value) {
    var hasPrototype = (this.prototype !== undefined),
        opts, key;

    if (hasPrototype === true) {
        opts = this.prototype.opts;
    } else if (this.opts === undefined) {
        opts = this.opts = {};
    } else {
        opts = this.opts;
    }

    if (option === undefined) {
        return opts;
    }

    if (value !== undefined) {
        opts[option] = value;
    } else if (key !== undefined) {
        for (key in option) {
            opts[key] = option[key];
        }
    }
}
```
- example usage
```shell
...
 * @param {function} callback - Callback
 */

['log', 'error', 'debug'].forEach(function (name) {
Command.prototype[name] = function (msg, prefixed) {
    if (msg instanceof Function) {
        this[name] = msg;
        this.instance.config(name, true);
    } else if (this.next !== undefined) {
        if (prefixed === undefined) {
            this.next[name]('(' + this.name + ') ' + msg, '');
        } else {
            this.next[name](msg, '');
        }
    } else if (this.instance.parent !== undefined) {
...
```

#### <a name="apidoc.element.osmosis.contains"></a>[function <span class="apidocSignatureSpan">osmosis.</span>contains (arg1, arg2, arg3)](#apidoc.element.osmosis.contains)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.cookie"></a>[function <span class="apidocSignatureSpan">osmosis.</span>cookie (arg1, arg2, arg3)](#apidoc.element.osmosis.cookie)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.data"></a>[function <span class="apidocSignatureSpan">osmosis.</span>data (arg1, arg2, arg3)](#apidoc.element.osmosis.data)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
    'description':  '#postingbody',
    'subcategory':  'div.breadbox > span[4]',
    'date':         'time@datetime',
    'latitude':     '#map@data-latitude',
    'longitude':    '#map@data-longitude',
    'images':       ['img@src']
})
.data(function(listing) {
    // do something with listing data
})
.log(console.log)
.error(console.log)
.debug(console.log)
'''
...
```

#### <a name="apidoc.element.osmosis.debug"></a>[function <span class="apidocSignatureSpan">osmosis.</span>debug (arg1, arg2, arg3)](#apidoc.element.osmosis.debug)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
    'images':       ['img@src']
})
.data(function(listing) {
    // do something with listing data
})
.log(console.log)
.error(console.log)
.debug(console.log)
'''

## Documentation

For documentation and examples check out [https://rchipka.github.io/node-osmosis/global.html](https://rchipka.github.io/node-osmosis
/global.html)

## Dependencies
...
```

#### <a name="apidoc.element.osmosis.delay"></a>[function <span class="apidocSignatureSpan">osmosis.</span>delay (arg1, arg2, arg3)](#apidoc.element.osmosis.delay)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.do"></a>[function <span class="apidocSignatureSpan">osmosis.</span>do (arg1, arg2, arg3)](#apidoc.element.osmosis.do)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.document"></a>[function <span class="apidocSignatureSpan">osmosis.</span>document (arg1, arg2, arg3)](#apidoc.element.osmosis.document)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.done"></a>[function <span class="apidocSignatureSpan">osmosis.</span>done (arg1, arg2, arg3)](#apidoc.element.osmosis.done)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...

if (--self.count === 0) {
    process.nextTick(function () {
        var instance;

        if (self.count === 0) {
            instance = self.instance;
            instance.command.done();

            if (instance.opts.debug === true) {
                instance.resources();
            }
        }
    });
}
...
```

#### <a name="apidoc.element.osmosis.else"></a>[function <span class="apidocSignatureSpan">osmosis.</span>else (arg1, arg2, arg3)](#apidoc.element.osmosis.else)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
 *
 * @property else
 * @private
 * @see {@link Command.if}
 */

get else() {
     return this.else();
 },

inherit: function (command) {
    command.instance = this.instance;

    return command;
},
...
```

#### <a name="apidoc.element.osmosis.end"></a>[function <span class="apidocSignatureSpan">osmosis.</span>end (arg1, arg2, arg3)](#apidoc.element.osmosis.end)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
    });

    return;
}

if (callback === undefined)  {
    if (next === undefined) {
        this.end(context, data);
    } else {
        next.start(context, data);
    }

    return;
}
...
```

#### <a name="apidoc.element.osmosis.error"></a>[function <span class="apidocSignatureSpan">osmosis.</span>error (arg1, arg2, arg3)](#apidoc.element.osmosis.error)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
    'longitude':    '#map@data-longitude',
    'images':       ['img@src']
})
.data(function(listing) {
    // do something with listing data
})
.log(console.log)
.error(console.log)
.debug(console.log)
'''

## Documentation

For documentation and examples check out [https://rchipka.github.io/node-osmosis/global.html](https://rchipka.github.io/node-osmosis
/global.html)
...
```

#### <a name="apidoc.element.osmosis.fail"></a>[function <span class="apidocSignatureSpan">osmosis.</span>fail (arg1, arg2, arg3)](#apidoc.element.osmosis.fail)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.filter"></a>[function <span class="apidocSignatureSpan">osmosis.</span>filter (arg1, arg2, arg3)](#apidoc.element.osmosis.filter)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.find"></a>[function <span class="apidocSignatureSpan">osmosis.</span>find (arg1, arg2, arg3)](#apidoc.element.osmosis.find)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
## Example

'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
...
```

#### <a name="apidoc.element.osmosis.findCommandArg"></a>[function <span class="apidocSignatureSpan">osmosis.</span>findCommandArg (arg1, arg2, arg3)](#apidoc.element.osmosis.findCommandArg)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...

args = new Array(length);

for (i = 0; i < length && arguments[i] !== undefined; i++) {
    args[i] = arguments[i];

    if (typeof args[i] === 'object') {
        args[i] = this.findCommandArg(args[i]);
    }
}

self.args = args;

if (func.length === 4) {
    self.cb = func;
...
```

#### <a name="apidoc.element.osmosis.follow"></a>[function <span class="apidocSignatureSpan">osmosis.</span>follow (arg1, arg2, arg3)](#apidoc.element.osmosis.follow)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
.follow('@href')
.set({
...
```

#### <a name="apidoc.element.osmosis.get"></a>[function <span class="apidocSignatureSpan">osmosis.</span>get (arg1, arg2, arg3)](#apidoc.element.osmosis.get)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...

## Example

'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
...
```

#### <a name="apidoc.element.osmosis.getInstance"></a>[function <span class="apidocSignatureSpan">osmosis.</span>getInstance (arg1, arg2, arg3)](#apidoc.element.osmosis.getInstance)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.getOpts"></a>[function <span class="apidocSignatureSpan">osmosis.</span>getOpts (arg1, arg2, arg3)](#apidoc.element.osmosis.getOpts)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
var proto;

if (this.opts !== undefined) {
    return this.opts;
}

if (this.prev !== undefined) {
    proto = this.prev.getOpts();
} else if (this.instance !== undefined) {
    proto = this.instance.opts;
}

this.opts = Object.create(proto);

return this.opts;
...
```

#### <a name="apidoc.element.osmosis.header"></a>[function <span class="apidocSignatureSpan">osmosis.</span>header (arg1, arg2, arg3)](#apidoc.element.osmosis.header)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.headers"></a>[function <span class="apidocSignatureSpan">osmosis.</span>headers (arg1, arg2, arg3)](#apidoc.element.osmosis.headers)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.if"></a>[function <span class="apidocSignatureSpan">osmosis.</span>if (arg1, arg2, arg3)](#apidoc.element.osmosis.if)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.inherit"></a>[function <span class="apidocSignatureSpan">osmosis.</span>inherit (arg1, arg2, arg3)](#apidoc.element.osmosis.inherit)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.isCommand"></a>[function <span class="apidocSignatureSpan">osmosis.</span>isCommand (arg1, arg2, arg3)](#apidoc.element.osmosis.isCommand)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.learn"></a>[function <span class="apidocSignatureSpan">osmosis.</span>learn (arg1, arg2, arg3)](#apidoc.element.osmosis.learn)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.log"></a>[function <span class="apidocSignatureSpan">osmosis.</span>log (arg1, arg2, arg3)](#apidoc.element.osmosis.log)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
    'latitude':     '#map@data-latitude',
    'longitude':    '#map@data-longitude',
    'images':       ['img@src']
})
.data(function(listing) {
    // do something with listing data
})
.log(console.log)
.error(console.log)
.debug(console.log)
'''

## Documentation

For documentation and examples check out [https://rchipka.github.io/node-osmosis/global.html](https://rchipka.github.io/node-osmosis
/global.html)
...
```

#### <a name="apidoc.element.osmosis.login"></a>[function <span class="apidocSignatureSpan">osmosis.</span>login (arg1, arg2, arg3)](#apidoc.element.osmosis.login)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.match"></a>[function <span class="apidocSignatureSpan">osmosis.</span>match (arg1, arg2, arg3)](#apidoc.element.osmosis.match)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.paginate"></a>[function <span class="apidocSignatureSpan">osmosis.</span>paginate (arg1, arg2, arg3)](#apidoc.element.osmosis.paginate)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
.follow('@href')
.set({
'title':        'section > h2',
'description':  '#postingbody',
'subcategory':  'div.breadbox > span[4]',
'date':         'time@datetime',
...
```

#### <a name="apidoc.element.osmosis.parse"></a>[function <span class="apidocSignatureSpan">osmosis.</span>parse (arg1, arg2, arg3)](#apidoc.element.osmosis.parse)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
    if (length === 3) {
        opts.parse = false;
    }

    if (context !== undefined) {
        document = context.doc();

        url = URL.parse(document.location.resolve(href), true);

        if (opts.follow_set_referer !== false) {
if (opts.headers === undefined) {
    opts.headers = {};
}

opts.headers.referer = document.location.href;
...
```

#### <a name="apidoc.element.osmosis.pause"></a>[function <span class="apidocSignatureSpan">osmosis.</span>pause (arg1, arg2, arg3)](#apidoc.element.osmosis.pause)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.post"></a>[function <span class="apidocSignatureSpan">osmosis.</span>post (arg1, arg2, arg3)](#apidoc.element.osmosis.post)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.proxy"></a>[function <span class="apidocSignatureSpan">osmosis.</span>proxy (arg1, arg2, arg3)](#apidoc.element.osmosis.proxy)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.request"></a>[function <span class="apidocSignatureSpan">osmosis.</span>request (arg1, arg2, arg3)](#apidoc.element.osmosis.request)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
                                       callback,
                                       tries) {
if (tries === undefined) {
    tries = 0;
}

if (this.queue.requests < this.opts.concurrency) {
    this.request(url, opts, callback, tries);
} else {
    this.queue.enqueue([url, opts, callback, tries]);
}
};

Osmosis.prototype.dequeueRequest = function () {
var arr, length = this.queue.length;
...
```

#### <a name="apidoc.element.osmosis.resume"></a>[function <span class="apidocSignatureSpan">osmosis.</span>resume (arg1, arg2, arg3)](#apidoc.element.osmosis.resume)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
}

if (instance.stopped === true) {
    return;
}

if (instance.paused  === true) {
    instance.resume(function () {
        self.start(context, data);
    });

    return;
}

if (callback === undefined)  {
...
```

#### <a name="apidoc.element.osmosis.rewrite"></a>[function <span class="apidocSignatureSpan">osmosis.</span>rewrite (arg1, arg2, arg3)](#apidoc.element.osmosis.rewrite)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.run"></a>[function <span class="apidocSignatureSpan">osmosis.</span>run (arg1, arg2, arg3)](#apidoc.element.osmosis.run)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
 *
 * // These instances start immediately
 * osmosis.get('http://example.com');
 * osmosis('http://example.com');
 *
 * // These instances need started
 * instance = new osmosis.get('http://example.com');
 * instance.run();
 *
 * instance = new osmosis('http://example.com');
 * instance.run();
 */

function Osmosis(url, params) {
if (url !== undefined) {
...
```

#### <a name="apidoc.element.osmosis.select"></a>[function <span class="apidocSignatureSpan">osmosis.</span>select (arg1, arg2, arg3)](#apidoc.element.osmosis.select)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.set"></a>[function <span class="apidocSignatureSpan">osmosis.</span>set (arg1, arg2, arg3)](#apidoc.element.osmosis.set)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...

'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
.follow('@href')
...
```

#### <a name="apidoc.element.osmosis.setInstance"></a>[function <span class="apidocSignatureSpan">osmosis.</span>setInstance (arg1, arg2, arg3)](#apidoc.element.osmosis.setInstance)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.setOpt"></a>[function <span class="apidocSignatureSpan">osmosis.</span>setOpt (arg1, arg2, arg3)](#apidoc.element.osmosis.setOpt)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.start"></a>[function <span class="apidocSignatureSpan">osmosis.</span>start (arg1, arg2, arg3)](#apidoc.element.osmosis.start)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
* @see {@link Command.run}
*/
Osmosis.prototype.run = function () {
   var self = this;

   process.nextTick(function () {
       self.started  = true;
       self.command.start();
   });
};

/**
* Make an HTTP request.
*
* @private
...
```

#### <a name="apidoc.element.osmosis.stop"></a>[function <span class="apidocSignatureSpan">osmosis.</span>stop (arg1, arg2, arg3)](#apidoc.element.osmosis.stop)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.submit"></a>[function <span class="apidocSignatureSpan">osmosis.</span>submit (arg1, arg2, arg3)](#apidoc.element.osmosis.submit)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.success"></a>[function <span class="apidocSignatureSpan">osmosis.</span>success (arg1, arg2, arg3)](#apidoc.element.osmosis.success)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.then"></a>[function <span class="apidocSignatureSpan">osmosis.</span>then (arg1, arg2, arg3)](#apidoc.element.osmosis.then)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
...
            case 'object':
                if (obj[key] !== null) {
                    obj[key] = this.findCommandArg(obj[key]);
                }

                break;
            case 'function':
                obj[key] = this.findCommandArg(this.then(obj[key]));
        }
    }

    return obj;
};

fs.readdirSync(cmdDir).forEach(function (file) {
...
```

#### <a name="apidoc.element.osmosis.train"></a>[function <span class="apidocSignatureSpan">osmosis.</span>train (arg1, arg2, arg3)](#apidoc.element.osmosis.train)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.trigger"></a>[function <span class="apidocSignatureSpan">osmosis.</span>trigger (arg1, arg2, arg3)](#apidoc.element.osmosis.trigger)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.use"></a>[function <span class="apidocSignatureSpan">osmosis.</span>use (arg1, arg2, arg3)](#apidoc.element.osmosis.use)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.using"></a>[function <span class="apidocSignatureSpan">osmosis.</span>using (arg1, arg2, arg3)](#apidoc.element.osmosis.using)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.window"></a>[function <span class="apidocSignatureSpan">osmosis.</span>window (arg1, arg2, arg3)](#apidoc.element.osmosis.window)
- description and source-code
```javascript
function StartingFunction(arg1, arg2, arg3) {
    var instance = new Osmosis(),
        command  = instance.command;

    instance.calledWithNew = (this instanceof StartingFunction);

    return command[name](arg1, arg2, arg3);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.osmosis.Command"></a>[module osmosis.Command](#apidoc.module.osmosis.Command)

#### <a name="apidoc.element.osmosis.Command.Command"></a>[function <span class="apidocSignatureSpan">osmosis.</span>Command (parent)](#apidoc.element.osmosis.Command.Command)
- description and source-code
```javascript
function Command(parent) {
    var self = this;

    if (Object.getPrototypeOf(parent) === Command.prototype) {
        // parent is a Command
        this.prev = parent;
        Object.defineProperty(this, 'instance', {
            get: Command.prototype.getInstance,
            set: Command.prototype.setInstance
        });
    } else if (parent !== undefined) {
        // 'parent' is an Osmosis instance
        this.instance = parent;
        // Call 'process.nextTick' so other instances can initialize
        process.nextTick(function () {
            // Attempt to auto-run the instance only IF:
            //  * Not already running
            //  * Not created using 'new'
            //  * Not a child instance
            if (parent.calledWithNew !== true &&
                parent.parent === undefined) {
                process.nextTick(function () {
                    // Run on nextTick to allow any
                    // runtimeCommands to finish first
                    parent.run();
                });
            }
        });
    }

    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.osmosis.Command.prototype"></a>[module osmosis.Command.prototype](#apidoc.module.osmosis.Command.prototype)

#### <a name="apidoc.element.osmosis.Command.prototype.click"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>click ()](#apidoc.element.osmosis.Command.prototype.click)
- description and source-code
```javascript
click = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.config"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>config ()](#apidoc.element.osmosis.Command.prototype.config)
- description and source-code
```javascript
config = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
...
 * @param {function} callback - Callback
 */

['log', 'error', 'debug'].forEach(function (name) {
Command.prototype[name] = function (msg, prefixed) {
    if (msg instanceof Function) {
        this[name] = msg;
        this.instance.config(name, true);
    } else if (this.next !== undefined) {
        if (prefixed === undefined) {
            this.next[name]('(' + this.name + ') ' + msg, '');
        } else {
            this.next[name](msg, '');
        }
    } else if (this.instance.parent !== undefined) {
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.contains"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>contains ()](#apidoc.element.osmosis.Command.prototype.contains)
- description and source-code
```javascript
contains = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.cookie"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>cookie ()](#apidoc.element.osmosis.Command.prototype.cookie)
- description and source-code
```javascript
cookie = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.data"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>data ()](#apidoc.element.osmosis.Command.prototype.data)
- description and source-code
```javascript
data = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
...
    'description':  '#postingbody',
    'subcategory':  'div.breadbox > span[4]',
    'date':         'time@datetime',
    'latitude':     '#map@data-latitude',
    'longitude':    '#map@data-longitude',
    'images':       ['img@src']
})
.data(function(listing) {
    // do something with listing data
})
.log(console.log)
.error(console.log)
.debug(console.log)
'''
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.debug"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>debug (msg, prefixed)](#apidoc.element.osmosis.Command.prototype.debug)
- description and source-code
```javascript
debug = function (msg, prefixed) {
    if (msg instanceof Function) {
        this[name] = msg;
        this.instance.config(name, true);
    } else if (this.next !== undefined) {
        if (prefixed === undefined) {
            this.next[name]('(' + this.name + ') ' + msg, '');
        } else {
            this.next[name](msg, '');
        }
    } else if (this.instance.parent !== undefined) {
        this.instance.parent[name](msg, true);
    }

    return this;
}
```
- example usage
```shell
...
    'images':       ['img@src']
})
.data(function(listing) {
    // do something with listing data
})
.log(console.log)
.error(console.log)
.debug(console.log)
'''

## Documentation

For documentation and examples check out [https://rchipka.github.io/node-osmosis/global.html](https://rchipka.github.io/node-osmosis
/global.html)

## Dependencies
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.delay"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>delay ()](#apidoc.element.osmosis.Command.prototype.delay)
- description and source-code
```javascript
delay = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.do"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>do ()](#apidoc.element.osmosis.Command.prototype.do)
- description and source-code
```javascript
do = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.done"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>done ()](#apidoc.element.osmosis.Command.prototype.done)
- description and source-code
```javascript
done = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
...

if (--self.count === 0) {
    process.nextTick(function () {
        var instance;

        if (self.count === 0) {
            instance = self.instance;
            instance.command.done();

            if (instance.opts.debug === true) {
                instance.resources();
            }
        }
    });
}
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.end"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>end (context, data)](#apidoc.element.osmosis.Command.prototype.end)
- description and source-code
```javascript
end = function (context, data) {
    var window, parent;

    // We're on the "sentinel node", meaning
    // We've reached the end of the command chain
    if (context !== undefined) {
        if (context.doc === undefined) {
            window = context.window;
        } else if (context.doc().__window !== undefined) {
            window = context.doc().defaultView;
        }

        if (window !== undefined) {
            // close 'window' when it reaches the last command
            window.close();
        }

        this.instance.queue.done++;
    }

    if (data !== undefined) {
        parent = data.parent;

        if (parent !== undefined) {
            if (data.isEmpty()) {
                data = data.clone();

                if (context.text !== undefined) {
                    data.setObject(context.text());
                } else if (context.value !== undefined) {
                    data.setObject(context.value());
                }
            }

            parent.merge(data);
            data.unref();
        }
    }
}
```
- example usage
```shell
...
    });

    return;
}

if (callback === undefined)  {
    if (next === undefined) {
        this.end(context, data);
    } else {
        next.start(context, data);
    }

    return;
}
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.error"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>error (msg, prefixed)](#apidoc.element.osmosis.Command.prototype.error)
- description and source-code
```javascript
error = function (msg, prefixed) {
    if (msg instanceof Function) {
        this[name] = msg;
        this.instance.config(name, true);
    } else if (this.next !== undefined) {
        if (prefixed === undefined) {
            this.next[name]('(' + this.name + ') ' + msg, '');
        } else {
            this.next[name](msg, '');
        }
    } else if (this.instance.parent !== undefined) {
        this.instance.parent[name](msg, true);
    }

    return this;
}
```
- example usage
```shell
...
    'longitude':    '#map@data-longitude',
    'images':       ['img@src']
})
.data(function(listing) {
    // do something with listing data
})
.log(console.log)
.error(console.log)
.debug(console.log)
'''

## Documentation

For documentation and examples check out [https://rchipka.github.io/node-osmosis/global.html](https://rchipka.github.io/node-osmosis
/global.html)
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.fail"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>fail ()](#apidoc.element.osmosis.Command.prototype.fail)
- description and source-code
```javascript
fail = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.filter"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>filter ()](#apidoc.element.osmosis.Command.prototype.filter)
- description and source-code
```javascript
filter = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.find"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>find ()](#apidoc.element.osmosis.Command.prototype.find)
- description and source-code
```javascript
find = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
...
## Example

'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.findCommandArg"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>findCommandArg (obj)](#apidoc.element.osmosis.Command.prototype.findCommandArg)
- description and source-code
```javascript
findCommandArg = function (obj) {
    var keys, key, length, i = 0;

    if (obj instanceof Command) {
        obj.instance.setParent(this);
        return obj.instance.command;
    }

    keys    = Object.keys(obj);
    length  = keys.length;

    for (; i < length; i++) {
        key = keys[i];
        switch (typeof obj[key]) {
            case 'object':
                if (obj[key] !== null) {
                    obj[key] = this.findCommandArg(obj[key]);
                }

                break;
            case 'function':
                obj[key] = this.findCommandArg(this.then(obj[key]));
        }
    }

    return obj;
}
```
- example usage
```shell
...

args = new Array(length);

for (i = 0; i < length && arguments[i] !== undefined; i++) {
    args[i] = arguments[i];

    if (typeof args[i] === 'object') {
        args[i] = this.findCommandArg(args[i]);
    }
}

self.args = args;

if (func.length === 4) {
    self.cb = func;
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.follow"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>follow ()](#apidoc.element.osmosis.Command.prototype.follow)
- description and source-code
```javascript
follow = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
...
'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
.follow('@href')
.set({
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.get"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>get ()](#apidoc.element.osmosis.Command.prototype.get)
- description and source-code
```javascript
get = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
...

## Example

'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.getInstance"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>getInstance ()](#apidoc.element.osmosis.Command.prototype.getInstance)
- description and source-code
```javascript
getInstance = function () {
    return this.prev.instance;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.getOpts"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>getOpts ()](#apidoc.element.osmosis.Command.prototype.getOpts)
- description and source-code
```javascript
getOpts = function () {
    var proto;

    if (this.opts !== undefined) {
        return this.opts;
    }

    if (this.prev !== undefined) {
        proto = this.prev.getOpts();
    } else if (this.instance !== undefined) {
        proto = this.instance.opts;
    }

    this.opts = Object.create(proto);

    return this.opts;
}
```
- example usage
```shell
...
var proto;

if (this.opts !== undefined) {
    return this.opts;
}

if (this.prev !== undefined) {
    proto = this.prev.getOpts();
} else if (this.instance !== undefined) {
    proto = this.instance.opts;
}

this.opts = Object.create(proto);

return this.opts;
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.header"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>header ()](#apidoc.element.osmosis.Command.prototype.header)
- description and source-code
```javascript
header = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.headers"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>headers ()](#apidoc.element.osmosis.Command.prototype.headers)
- description and source-code
```javascript
headers = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.if"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>if ()](#apidoc.element.osmosis.Command.prototype.if)
- description and source-code
```javascript
if = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.inherit"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>inherit (command)](#apidoc.element.osmosis.Command.prototype.inherit)
- description and source-code
```javascript
inherit = function (command) {
    command.instance = this.instance;

    return command;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.learn"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>learn ()](#apidoc.element.osmosis.Command.prototype.learn)
- description and source-code
```javascript
learn = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.log"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>log (msg, prefixed)](#apidoc.element.osmosis.Command.prototype.log)
- description and source-code
```javascript
log = function (msg, prefixed) {
    if (msg instanceof Function) {
        this[name] = msg;
        this.instance.config(name, true);
    } else if (this.next !== undefined) {
        if (prefixed === undefined) {
            this.next[name]('(' + this.name + ') ' + msg, '');
        } else {
            this.next[name](msg, '');
        }
    } else if (this.instance.parent !== undefined) {
        this.instance.parent[name](msg, true);
    }

    return this;
}
```
- example usage
```shell
...
    'latitude':     '#map@data-latitude',
    'longitude':    '#map@data-longitude',
    'images':       ['img@src']
})
.data(function(listing) {
    // do something with listing data
})
.log(console.log)
.error(console.log)
.debug(console.log)
'''

## Documentation

For documentation and examples check out [https://rchipka.github.io/node-osmosis/global.html](https://rchipka.github.io/node-osmosis
/global.html)
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.login"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>login ()](#apidoc.element.osmosis.Command.prototype.login)
- description and source-code
```javascript
login = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.match"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>match ()](#apidoc.element.osmosis.Command.prototype.match)
- description and source-code
```javascript
match = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.paginate"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>paginate ()](#apidoc.element.osmosis.Command.prototype.paginate)
- description and source-code
```javascript
paginate = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
...
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
.follow('@href')
.set({
'title':        'section > h2',
'description':  '#postingbody',
'subcategory':  'div.breadbox > span[4]',
'date':         'time@datetime',
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.parse"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>parse ()](#apidoc.element.osmosis.Command.prototype.parse)
- description and source-code
```javascript
parse = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
...
    if (length === 3) {
        opts.parse = false;
    }

    if (context !== undefined) {
        document = context.doc();

        url = URL.parse(document.location.resolve(href), true);

        if (opts.follow_set_referer !== false) {
if (opts.headers === undefined) {
    opts.headers = {};
}

opts.headers.referer = document.location.href;
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.pause"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>pause ()](#apidoc.element.osmosis.Command.prototype.pause)
- description and source-code
```javascript
pause = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.post"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>post ()](#apidoc.element.osmosis.Command.prototype.post)
- description and source-code
```javascript
post = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.proxy"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>proxy ()](#apidoc.element.osmosis.Command.prototype.proxy)
- description and source-code
```javascript
proxy = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.request"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>request (method, context, href, params, callback)](#apidoc.element.osmosis.Command.prototype.request)
- description and source-code
```javascript
request = function (method, context, href, params, callback) {
    var self     = this,
        length   = callback.length,
        instance = self.instance,
        opts     = Object.create(this.getOpts()),
        url, document, key, proxies;

    if (!href || href.length === 0) {
        callback("Invalid URL");
        return;
    }

    if (length === 3) {
        opts.parse = false;
    }

    if (context !== undefined) {
        document = context.doc();

        url = URL.parse(document.location.resolve(href), true);

        if (opts.follow_set_referer !== false) {
            if (opts.headers === undefined) {
                opts.headers = {};
            }

            opts.headers.referer = document.location.href;
        }

        if (opts.cookies !== undefined) {
            if (document.cookies === undefined) {
                document.cookies = {};
            }

            opts.cookies = extend(document.cookies, opts.cookies);
        } else {
            opts.cookies = document.cookies;
        }

        if (method === 'post') {
            // Check the enctype if submitting a form
            if (formFunctions.isMultipart(context)) {
                opts.multipart = true;
            }
        }
    } else if (href.substr(0, 1) === '//') {
        url = URL.parse('http:' + href, true);
    } else if (href.substr(0, 4) !== 'http') {
        url = URL.parse('http://' + href, true);
    } else {
        url = URL.parse(href, true);
    }

    url.method = method;
    url.params = params;

    if (method === 'get') {
        for (key in params) {
            url.query[key] = params[key];
        }

        url.params = url.query;
        url.search = qs.stringify(url.query);
        url.href   = URL.format(url);
    }

    if (Array.isArray(opts.proxy)) {
        opts.proxies = opts.proxy;
    }

    if (opts.proxies !== undefined) {
        proxies = opts.proxies;

        if (proxies.index === undefined || ++proxies.index >= proxies.length) {
            proxies.index = 0;
        }

        opts.proxy = proxies[proxies.index];
    }

    instance.queueRequest(url, opts,
    function (err, res, document) {
        if (err !== null) {
            self.error((self.name !== method ?
                        '[' + method + '] ' :
                        '') + (url.href) + ' - ' + err);

            if (length === 2) {
                callback(err, document);
            } else if (length === 3) {
                callback(err, res, document);
            }
        } else {
            self.log('loaded [' + method + '] ' + url.href + ' ' +
                (params ?
                JSON.stringify(params) :
                '') +
                (opts.proxy ?
                ' via ' + opts.proxy :
                '')
            );

            if (length === 1) {
                callback(document);
            } else if (length === 2) {
                callback(null, document);
            } else {
                callback(null, res, document);
            }
        }
    });
}
```
- example usage
```shell
...
                                       callback,
                                       tries) {
if (tries === undefined) {
    tries = 0;
}

if (this.queue.requests < this.opts.concurrency) {
    this.request(url, opts, callback, tries);
} else {
    this.queue.enqueue([url, opts, callback, tries]);
}
};

Osmosis.prototype.dequeueRequest = function () {
var arr, length = this.queue.length;
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.resume"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>resume ()](#apidoc.element.osmosis.Command.prototype.resume)
- description and source-code
```javascript
resume = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
...
}

if (instance.stopped === true) {
    return;
}

if (instance.paused  === true) {
    instance.resume(function () {
        self.start(context, data);
    });

    return;
}

if (callback === undefined)  {
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.rewrite"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>rewrite ()](#apidoc.element.osmosis.Command.prototype.rewrite)
- description and source-code
```javascript
rewrite = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.run"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>run (context, data)](#apidoc.element.osmosis.Command.prototype.run)
- description and source-code
```javascript
run = function (context, data) {
    return this.instance.run(context, data);
}
```
- example usage
```shell
...
 *
 * // These instances start immediately
 * osmosis.get('http://example.com');
 * osmosis('http://example.com');
 *
 * // These instances need started
 * instance = new osmosis.get('http://example.com');
 * instance.run();
 *
 * instance = new osmosis('http://example.com');
 * instance.run();
 */

function Osmosis(url, params) {
if (url !== undefined) {
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.select"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>select ()](#apidoc.element.osmosis.Command.prototype.select)
- description and source-code
```javascript
select = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.set"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>set ()](#apidoc.element.osmosis.Command.prototype.set)
- description and source-code
```javascript
set = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
...

'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
.follow('@href')
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.setInstance"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>setInstance (val)](#apidoc.element.osmosis.Command.prototype.setInstance)
- description and source-code
```javascript
setInstance = function (val) {
    return (this.prev.instance = val);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.setOpt"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>setOpt (name, value)](#apidoc.element.osmosis.Command.prototype.setOpt)
- description and source-code
```javascript
setOpt = function (name, value) {
    var opts = this.getOpts();

    if (value !== null &&
        value instanceof Object &&
        opts[name] !== null &&
        opts[name] instanceof Object) {
        opts[name] = extend(value, opts[name]);
    } else {
        opts[name] = value;
    }

    return opts;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.start"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>start (context, data)](#apidoc.element.osmosis.Command.prototype.start)
- description and source-code
```javascript
start = function (context, data) {
    var self        = this,
        next        = this.next,
        instance    = this.instance,
        callback    = this.cb,
        calledNext  = false,
        window;

    if (context === null) {
        return;
    }

    if (instance.stopped === true) {
        return;
    }

    if (instance.paused  === true) {
        instance.resume(function () {
            self.start(context, data);
        });

        return;
    }

    if (callback === undefined)  {
        if (next === undefined) {
            this.end(context, data);
        } else {
            next.start(context, data);
        }

        return;
    }

    instance.queue.push();

    if (data === undefined) {
        data = (new Data());
    }

    data.ref();

    return callback.call(this, context, data, function (c, d) {
        if (calledNext === true) {
            // If 'next' is called more than once,
            // then we need to clone the data
            next.start(c, d.clone().ref());
        } else {
            calledNext = true;
            next.start(c, d);
        }
    }, function (err) {
        data.unref();

        if (calledNext !== true) {
            self.end(context, data);
        }

        if (err !== undefined) {
            self.error(err);
        }

        instance.queue.pop();
    });
}
```
- example usage
```shell
...
* @see {@link Command.run}
*/
Osmosis.prototype.run = function () {
   var self = this;

   process.nextTick(function () {
       self.started  = true;
       self.command.start();
   });
};

/**
* Make an HTTP request.
*
* @private
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.stop"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>stop ()](#apidoc.element.osmosis.Command.prototype.stop)
- description and source-code
```javascript
stop = function () {
    var length   = arguments.length,
        self = this, args, i;

    if (length === 0) {
        // Allow '.config()', etc. to get configuration
        // options during command chain compile time
        return func.call(self);
    }

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];
    }

    process.nextTick(function () {
        if (self.next !== undefined) {
            // We're NOT on the last command, so we call 'func' in the
            // context of the PRECEEDING command
            func.apply(self.prev, args);
        } else {
            // We're on the last command, so we call 'func' in the
            // context of the FIRST command
            func.apply(self.instance.command, args);
        }
    });

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.submit"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>submit ()](#apidoc.element.osmosis.Command.prototype.submit)
- description and source-code
```javascript
submit = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.success"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>success ()](#apidoc.element.osmosis.Command.prototype.success)
- description and source-code
```javascript
success = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.then"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>then ()](#apidoc.element.osmosis.Command.prototype.then)
- description and source-code
```javascript
then = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
...
            case 'object':
                if (obj[key] !== null) {
                    obj[key] = this.findCommandArg(obj[key]);
                }

                break;
            case 'function':
                obj[key] = this.findCommandArg(this.then(obj[key]));
        }
    }

    return obj;
};

fs.readdirSync(cmdDir).forEach(function (file) {
...
```

#### <a name="apidoc.element.osmosis.Command.prototype.train"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>train ()](#apidoc.element.osmosis.Command.prototype.train)
- description and source-code
```javascript
train = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.trigger"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>trigger ()](#apidoc.element.osmosis.Command.prototype.trigger)
- description and source-code
```javascript
trigger = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.use"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>use ()](#apidoc.element.osmosis.Command.prototype.use)
- description and source-code
```javascript
use = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Command.prototype.using"></a>[function <span class="apidocSignatureSpan">osmosis.Command.prototype.</span>using ()](#apidoc.element.osmosis.Command.prototype.using)
- description and source-code
```javascript
using = function () {
    var length   = arguments.length,
        self, i, args;

    if (this.name === undefined) {
        self = this;
    } else {
        self = new Command(this);
    }

    self.name = name;

    args = new Array(length);

    for (i = 0; i < length && arguments[i] !== undefined; i++) {
        args[i] = arguments[i];

        if (typeof args[i] === 'object') {
            args[i] = this.findCommandArg(args[i]);
        }
    }

    self.args = args;

    if (func.length === 4) {
        self.cb = func;
    } else {
        self.cb = func.apply(self, self.args);
    }

    self.next = new Command(self);

    return self.next;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.osmosis.Data"></a>[module osmosis.Data](#apidoc.module.osmosis.Data)

#### <a name="apidoc.element.osmosis.Data.Data"></a>[function <span class="apidocSignatureSpan">osmosis.</span>Data (parent)](#apidoc.element.osmosis.Data.Data)
- description and source-code
```javascript
function Data(parent) {
    this.stack = { count: 0 };

    if (parent) {
        this.parent = parent;
    }

    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.osmosis.Data.prototype"></a>[module osmosis.Data.prototype](#apidoc.module.osmosis.Data.prototype)

#### <a name="apidoc.element.osmosis.Data.prototype.child"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>child ()](#apidoc.element.osmosis.Data.prototype.child)
- description and source-code
```javascript
child = function () {
    return new Data(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Data.prototype.clone"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>clone ()](#apidoc.element.osmosis.Data.prototype.clone)
- description and source-code
```javascript
clone = function () {
    var clone    = this.next();

    clone.object = this.copy();

    return clone;
}
```
- example usage
```shell
...

data.ref();

return callback.call(this, context, data, function (c, d) {
    if (calledNext === true) {
        // If 'next' is called more than once,
        // then we need to clone the data
        next.start(c, d.clone().ref());
    } else {
        calledNext = true;
        next.start(c, d);
    }
}, function (err) {
    data.unref();
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.copy"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>copy ()](#apidoc.element.osmosis.Data.prototype.copy)
- description and source-code
```javascript
copy = function () {
    var obj = this.object,
        data, i, keys, key;

    if (this.isArray()) {
        data = obj.slice(0);
    } else if (obj instanceof Object) {
        data = {};

        for (i = 0, keys = Object.keys(obj); i < keys.length; i++) {
            key = keys[i];
            data[key] = obj[key];
        }
    } else {
        data = obj;
    }

    return data;
}
```
- example usage
```shell
...
* Clone a Data object.
*
*/

Data.prototype.clone = function () {
   var clone    = this.next();

   clone.object = this.copy();

   return clone;
};

/**
* Call callback when 'Data.stack.count' === 0.
*/
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.done"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>done (cb)](#apidoc.element.osmosis.Data.prototype.done)
- description and source-code
```javascript
done = function (cb) {
    this.stack.done = cb;
    return this;
}
```
- example usage
```shell
...

if (--self.count === 0) {
    process.nextTick(function () {
        var instance;

        if (self.count === 0) {
            instance = self.instance;
            instance.command.done();

            if (instance.opts.debug === true) {
                instance.resources();
            }
        }
    });
}
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.extend"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>extend (object)](#apidoc.element.osmosis.Data.prototype.extend)
- description and source-code
```javascript
extend = function (object) {
    var key, keys = Object.keys(object),
        isArray = this.isArray(),
        i = keys.length;

    while (i--) {
        key = keys[i];

        if (isArray) {
            this.push(object[key]);
        } else {
            this.set(key, object[key]);
        }
    }

    return object;
}
```
- example usage
```shell
...
}

if (this.isArray() === true) {
    this.push(object);
} else if (index !== undefined) {
    this.set(child.getIndex(), object);
} else if (object instanceof Object) {
    this.extend(object);
}
};

Data.prototype.toArray = function () {
var object = this.object;

if (object instanceof Array) {
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.getIndex"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>getIndex ()](#apidoc.element.osmosis.Data.prototype.getIndex)
- description and source-code
```javascript
getIndex = function () {
    return this._index;
}
```
- example usage
```shell
...
/**
 * Create a new Data object to pass to the next Command.
 *
 */

Data.prototype.next = function () {
    var clone = new Data(this.parent)
                    .setIndex(this.getIndex())
                    .isArray(this.isArray());

    clone.stack  = this.stack;
    clone.object = this.object;
    return clone;
};
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.getObject"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>getObject ()](#apidoc.element.osmosis.Data.prototype.getObject)
- description and source-code
```javascript
getObject = function () {
    if (this.object === undefined) {
        if (this.isArray() === true) {
            this.toArray();
        } else {
            this.setObject({});
        }
    }

    return this.object;
}
```
- example usage
```shell
...
    return this;
}

if (this.isArray() === true) {
    return this.push(val);
}

object     = this.getObject();
currentVal = object[key];

if (currentVal !== undefined) {
    // If the key being set already has a value,
    // then convert it to an Array.
    if (currentVal instanceof Array) {
        currentVal.push(val);
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.isArray"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>isArray (val)](#apidoc.element.osmosis.Data.prototype.isArray)
- description and source-code
```javascript
isArray = function (val) {
    if (val !== undefined) {
        this._isArray = val === true;
        return this;
    }

    return (this._isArray === true || this.object instanceof Array);
}
```
- example usage
```shell
...
}

url.params = url.query;
url.search = qs.stringify(url.query);
url.href   = URL.format(url);
    }

    if (Array.isArray(opts.proxy)) {
opts.proxies = opts.proxy;
    }

    if (opts.proxies !== undefined) {
proxies = opts.proxies;

if (proxies.index === undefined || ++proxies.index >= proxies.length) {
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>isEmpty ()](#apidoc.element.osmosis.Data.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
    return (this.object === undefined ||
            (this.object instanceof Object &&
             Object.keys(this.object).length === 0)
            );
}
```
- example usage
```shell
...
        this.instance.queue.done++;
    }

    if (data !== undefined) {
        parent = data.parent;

        if (parent !== undefined) {
            if (data.isEmpty()) {
data = data.clone();

if (context.text !== undefined) {
    data.setObject(context.text());
} else if (context.value !== undefined) {
    data.setObject(context.value());
}
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.merge"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>merge (child)](#apidoc.element.osmosis.Data.prototype.merge)
- description and source-code
```javascript
merge = function (child) {
    var object = child.object,
        index  = child.getIndex();

    if (object === undefined) {
        return;
    }

    if (this.isArray() === true) {
        this.push(object);
    } else if (index !== undefined) {
        this.set(child.getIndex(), object);
    } else if (object instanceof Object) {
        this.extend(object);
    }
}
```
- example usage
```shell
...
               if (context.text !== undefined) {
                   data.setObject(context.text());
               } else if (context.value !== undefined) {
                   data.setObject(context.value());
               }
           }

           parent.merge(data);
           data.unref();
       }
   }
};

/**
* Get the current options and inherit previous options.
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.next"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>next ()](#apidoc.element.osmosis.Data.prototype.next)
- description and source-code
```javascript
next = function () {
    var clone = new Data(this.parent)
                    .setIndex(this.getIndex())
                    .isArray(this.isArray());

    clone.stack  = this.stack;
    clone.object = this.object;
    return clone;
}
```
- example usage
```shell
...

/**
 * Clone a Data object.
 *
 */

Data.prototype.clone = function () {
    var clone    = this.next();

    clone.object = this.copy();

    return clone;
};

/**
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.push"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>push (val)](#apidoc.element.osmosis.Data.prototype.push)
- description and source-code
```javascript
push = function (val) {
    var object = this.toArray();

    if (val === undefined) {
        return this;
    }

    object.push(val);

    return this;
}
```
- example usage
```shell
...
var self = this,
    href   = url.href,
    method = url.method,
    params = url.params;

this.requests++;
this.queue.requests++;
this.queue.push();

request(url.method,
        url,
        url.params,
        opts,
        tries,
        function (err, res, data) {
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.ref"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>ref ()](#apidoc.element.osmosis.Data.prototype.ref)
- description and source-code
```javascript
ref = function () {
    this.stack.count++;
    return this;
}
```
- example usage
```shell
...

instance.queue.push();

if (data === undefined) {
    data = (new Data());
}

data.ref();

return callback.call(this, context, data, function (c, d) {
    if (calledNext === true) {
        // If 'next' is called more than once,
        // then we need to clone the data
        next.start(c, d.clone().ref());
    } else {
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.set"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>set (key, val)](#apidoc.element.osmosis.Data.prototype.set)
- description and source-code
```javascript
set = function (key, val) {
    var object, currentVal;

    if (val === undefined) {
        return this;
    }

    if (this.isArray() === true) {
        return this.push(val);
    }

    object     = this.getObject();
    currentVal = object[key];

    if (currentVal !== undefined) {
        // If the key being set already has a value,
        // then convert it to an Array.
        if (currentVal instanceof Array) {
            currentVal.push(val);
        } else {
            object[key] = [currentVal, val];
        }
    } else {
        object[key] = val;
    }

    return this;
}
```
- example usage
```shell
...

'''javascript
var osmosis = require('osmosis');

osmosis
.get('www.craigslist.org/about/sites')
.find('h1 + div a')
.set('location')
.follow('@href')
.find('header + div + div li > a')
.set('category')
.follow('@href')
.paginate('.totallink + a.button.next:first')
.find('p > a')
.follow('@href')
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.setIndex"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>setIndex (index)](#apidoc.element.osmosis.Data.prototype.setIndex)
- description and source-code
```javascript
setIndex = function (index) {
    if (this.isArray() !== true) {
        this._index = index;
    }

    return this;
}
```
- example usage
```shell
...
/**
 * Create a new Data object to pass to the next Command.
 *
 */

Data.prototype.next = function () {
    var clone = new Data(this.parent)
                    .setIndex(this.getIndex())
                    .isArray(this.isArray());

    clone.stack  = this.stack;
    clone.object = this.object;
    return clone;
};
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.setObject"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>setObject (object)](#apidoc.element.osmosis.Data.prototype.setObject)
- description and source-code
```javascript
setObject = function (object) {
    this.object = object;

    return this;
}
```
- example usage
```shell
...
        parent = data.parent;

        if (parent !== undefined) {
if (data.isEmpty()) {
    data = data.clone();

    if (context.text !== undefined) {
        data.setObject(context.text());
    } else if (context.value !== undefined) {
        data.setObject(context.value());
    }
}

parent.merge(data);
data.unref();
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.toArray"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>toArray ()](#apidoc.element.osmosis.Data.prototype.toArray)
- description and source-code
```javascript
toArray = function () {
    var object = this.object;

    if (object instanceof Array) {
        return object;
    }

    if (this.isEmpty()) {
        this.setObject([]);
    } else {
        this.setObject([ object ]);
    }

    return this.getObject();
}
```
- example usage
```shell
...
 * Get the raw data object.
 *
 */

Data.prototype.getObject = function () {
    if (this.object === undefined) {
        if (this.isArray() === true) {
            this.toArray();
        } else {
            this.setObject({});
        }
    }

    return this.object;
};
...
```

#### <a name="apidoc.element.osmosis.Data.prototype.unref"></a>[function <span class="apidocSignatureSpan">osmosis.Data.prototype.</span>unref ()](#apidoc.element.osmosis.Data.prototype.unref)
- description and source-code
```javascript
unref = function () {
    if (--this.stack.count === 0) {
        if (this.stack.done !== undefined) {
            this.stack.done.call(this);
        }
    }
}
```
- example usage
```shell
...
    // then we need to clone the data
    next.start(c, d.clone().ref());
} else {
    calledNext = true;
    next.start(c, d);
}
    }, function (err) {
data.unref();

if (calledNext !== true) {
    self.end(context, data);
}

if (err !== undefined) {
    self.error(err);
...
```



# <a name="apidoc.module.osmosis.Form"></a>[module osmosis.Form](#apidoc.module.osmosis.Form)

#### <a name="apidoc.element.osmosis.Form.getAction"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>getAction (node)](#apidoc.element.osmosis.Form.getAction)
- description and source-code
```javascript
getAction = function (node) {
    var document = node.doc();

    if (node.hasAttribute('action')) {
        return document.location.resolve(node.getAttribute('action'));
    } else if (node.hasAttribute('formaction')) {
        return document.location.resolve(node.getAttribute('formaction'));
    } else {
        return document.location.href;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Form.getEnctype"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>getEnctype (node)](#apidoc.element.osmosis.Form.getEnctype)
- description and source-code
```javascript
getEnctype = function (node) {
    if (node.hasAttribute('enctype')) {
        return node.getAttribute('enctype');
    } else if (node.hasAttribute('formenctype')) {
        return node.getAttribute('formenctype');
    }

    return 'application/x-www-form-urlencoded';
}
```
- example usage
```shell
...
};

form.isMultipart = function (node) {
if (node.hasAttribute === undefined) {
    return false;
}

return (form.getEnctype(node).substr(0, 5) === 'multi');
};

form.getMethod = function (node) {
if (node.hasAttribute('method')) {
    return node.getAttribute('method').toLowerCase();
} else if (node.hasAttribute('formmethod')) {
    return node.getAttribute('formmethod').toLowerCase();
...
```

#### <a name="apidoc.element.osmosis.Form.getForm"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>getForm (node)](#apidoc.element.osmosis.Form.getForm)
- description and source-code
```javascript
getForm = function (node) {
    if (form.isForm(node)) {
        return node;
    } else if (node.hasAttribute('form')) {
        return node.doc().getElementById(node.getAttribute('form'));
    } else {
        return node.get('ancestor-or-self::form');
    }
}
```
- example usage
```shell
...
    return node.doc().getElementById(node.getAttribute('form'));
} else {
    return node.get('ancestor-or-self::form');
}
};

form.getInputs = function (node) {
return form.getForm(node).find('[@name ' +
                        'and not(@disabled) ' +
                        'and not(@type="submit")]');
};

form.getSubmitButton = function (node) {
if (form.isForm(node)) {
    return node.get('[@type="submit" and not(@disabled) and ' +
...
```

#### <a name="apidoc.element.osmosis.Form.getInputs"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>getInputs (node)](#apidoc.element.osmosis.Form.getInputs)
- description and source-code
```javascript
getInputs = function (node) {
    return form.getForm(node).find('[@name ' +
                            'and not(@disabled) ' +
                            'and not(@type="submit")]');
}
```
- example usage
```shell
...
    return 'get';
}
};

form.getParams = function (node) {
var params = {},
    submit = form.getSubmitButton(node),
    inputs = form.getInputs(node),
    length = inputs.length,
    i = 0, input, name, nodeName, type, value;

for (i = 0; i < length; i++) {
    input = inputs[i];
    name = input.getAttribute('name');
    type = input.getAttribute('type');
...
```

#### <a name="apidoc.element.osmosis.Form.getMethod"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>getMethod (node)](#apidoc.element.osmosis.Form.getMethod)
- description and source-code
```javascript
getMethod = function (node) {
    if (node.hasAttribute('method')) {
        return node.getAttribute('method').toLowerCase();
    } else if (node.hasAttribute('formmethod')) {
        return node.getAttribute('formmethod').toLowerCase();
    } else {
        return 'get';
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Form.getParams"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>getParams (node)](#apidoc.element.osmosis.Form.getParams)
- description and source-code
```javascript
getParams = function (node) {
    var params = {},
        submit = form.getSubmitButton(node),
        inputs = form.getInputs(node),
        length = inputs.length,
        i = 0, input, name, nodeName, type, value;

    for (i = 0; i < length; i++) {
        input = inputs[i];
        name = input.getAttribute('name');
        type = input.getAttribute('type');
        nodeName = input.nodeName;
        value = null;

        if (name.charAt(name.length - 1) === ']') {
            name = name.substr(0, name.length - 2);
        }

        if (type) {
            type = type.toLowerCase();
        }

        switch (nodeName) {
            case 'select':
                input = input.get('option[selected]') ||
                        input.get('option:first');

                if (input !== null) {
                    if (input.hasAttribute('value')) {
                        value = input.getAttribute('value');
                    } else {
                        value = input.textContent;
                    }
                }

                break;
            case 'textarea':
                value = input.textContent;
                break;
            case 'input':
                switch (type) {
                    case 'radio':
                    case 'image':
                        ['x', 'y'].forEach(function (p) {
                            var array = [];

                            if (name) {
                                array.push(name);
                            }

                            array.push(p);

                            params[array.join('.')] = 0;
                        });
                    case 'checkbox':
                        if (!input.hasAttribute('checked'))  {
                            break;
                        }

                        name  = name.replace(/\[\]$/, '');
                        value = input.getAttribute('value') || 'on';

                        break;
                    default:
                        value = input.getAttribute('value');
                        break;

                }
                break;
        }

        if (value !== null) {
            if (params[name] instanceof Array) {
                params[name].push(value);
            } else if (params[name] !== undefined) {
                params[name] = [params[name], value];
            } else {
                params[name] = value;
            }
        }
    }

    if (submit !== null) {
        if (submit.hasAttribute('name')) {
            params[submit.getAttribute('name')] =
                submit.getAttribute('value') || 'Submit Query';
        }
    }

    return params;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.osmosis.Form.getSubmitButton"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>getSubmitButton (node)](#apidoc.element.osmosis.Form.getSubmitButton)
- description and source-code
```javascript
getSubmitButton = function (node) {
    if (form.isForm(node)) {
        return node.get('[@type="submit" and not(@disabled) and ' +
                        '(not(@form) or @form="' +
                            node.getAttribute('id') + '"' +
                        ')][1]');
    } else if ((node.nodeName === 'input' || node.nodeName === 'button') &&
                node.getAttribute('type') === 'submit') {
        return node;
    }

    return null;
}
```
- example usage
```shell
...
} else {
    return 'get';
}
};

form.getParams = function (node) {
var params = {},
    submit = form.getSubmitButton(node),
    inputs = form.getInputs(node),
    length = inputs.length,
    i = 0, input, name, nodeName, type, value;

for (i = 0; i < length; i++) {
    input = inputs[i];
    name = input.getAttribute('name');
...
```

#### <a name="apidoc.element.osmosis.Form.isForm"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>isForm (node)](#apidoc.element.osmosis.Form.isForm)
- description and source-code
```javascript
isForm = function (node) {
    return node.nodeName === 'form';
}
```
- example usage
```shell
...
};

form.isForm = function (node) {
    return node.nodeName === 'form';
};

form.getForm = function (node) {
    if (form.isForm(node)) {
        return node;
    } else if (node.hasAttribute('form')) {
        return node.doc().getElementById(node.getAttribute('form'));
    } else {
        return node.get('ancestor-or-self::form');
    }
};
...
```

#### <a name="apidoc.element.osmosis.Form.isMultipart"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>isMultipart (node)](#apidoc.element.osmosis.Form.isMultipart)
- description and source-code
```javascript
isMultipart = function (node) {
    if (node.hasAttribute === undefined) {
        return false;
    }

    return (form.getEnctype(node).substr(0, 5) === 'multi');
}
```
- example usage
```shell
...
        opts.cookies = extend(document.cookies, opts.cookies);
    } else {
        opts.cookies = document.cookies;
    }

    if (method === 'post') {
        // Check the enctype if submitting a form
        if (formFunctions.isMultipart(context)) {
            opts.multipart = true;
        }
    }
} else if (href.substr(0, 1) === '//') {
    url = URL.parse('http:' + href, true);
} else if (href.substr(0, 4) !== 'http') {
    url = URL.parse('http://' + href, true);
...
```

#### <a name="apidoc.element.osmosis.Form.submit"></a>[function <span class="apidocSignatureSpan">osmosis.Form.</span>submit ()](#apidoc.element.osmosis.Form.submit)
- description and source-code
```javascript
submit = function () {

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.osmosis.Queue"></a>[module osmosis.Queue](#apidoc.module.osmosis.Queue)

#### <a name="apidoc.element.osmosis.Queue.Queue"></a>[function <span class="apidocSignatureSpan">osmosis.</span>Queue (instance)](#apidoc.element.osmosis.Queue.Queue)
- description and source-code
```javascript
function Queue(instance) {
    this.instance = instance;
    this.opts = instance.opts;
    this.queue = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.osmosis.Queue.prototype"></a>[module osmosis.Queue.prototype](#apidoc.module.osmosis.Queue.prototype)

#### <a name="apidoc.element.osmosis.Queue.prototype.dequeue"></a>[function <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>dequeue ()](#apidoc.element.osmosis.Queue.prototype.dequeue)
- description and source-code
```javascript
dequeue = function () {
    var object = this.queue[--this.length];

    this.queue[this.length] = null;

    return object;
}
```
- example usage
```shell
...
Osmosis.prototype.dequeueRequest = function () {
   var arr, length = this.queue.length;

   if (length === 0 || this.queue.requests >= this.opts.concurrency) {
       return;
   }

   arr = this.queue.dequeue();

   this.request(arr[0], arr[1], arr[2], arr[3]);
};

/**
* Parse XML/HTML data.
*
...
```

#### <a name="apidoc.element.osmosis.Queue.prototype.enqueue"></a>[function <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>enqueue (object)](#apidoc.element.osmosis.Queue.prototype.enqueue)
- description and source-code
```javascript
enqueue = function (object) {
    this.queue[this.length++] = object;
}
```
- example usage
```shell
...
if (tries === undefined) {
    tries = 0;
}

if (this.queue.requests < this.opts.concurrency) {
    this.request(url, opts, callback, tries);
} else {
    this.queue.enqueue([url, opts, callback, tries]);
}
};

Osmosis.prototype.dequeueRequest = function () {
var arr, length = this.queue.length;

if (length === 0 || this.queue.requests >= this.opts.concurrency) {
...
```

#### <a name="apidoc.element.osmosis.Queue.prototype.pop"></a>[function <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>pop ()](#apidoc.element.osmosis.Queue.prototype.pop)
- description and source-code
```javascript
pop = function () {
    var self = this;

    if (--self.count === 0) {
        process.nextTick(function () {
            var instance;

            if (self.count === 0) {
                instance = self.instance;
                instance.command.done();

                if (instance.opts.debug === true) {
                    instance.resources();
                }
            }
        });
    }

    this.change++;

    return this.count;
}
```
- example usage
```shell
...
                            opts.tries + ')');
        }
    } else {
        callback(err, res, data);
    }

    self.dequeueRequest();
    self.queue.pop();
})
.on('redirect', function (new_url) {
    if (self.opts.log === true) {
        self.command.log('[redirect] ' +
                         href + ' -> ' + new_url);
    }
});
...
```

#### <a name="apidoc.element.osmosis.Queue.prototype.push"></a>[function <span class="apidocSignatureSpan">osmosis.Queue.prototype.</span>push ()](#apidoc.element.osmosis.Queue.prototype.push)
- description and source-code
```javascript
push = function () {
    if (++this.change >= 25) {
        if (this.instance.resources !== null) {
            this.instance.resources();
        }

        this.change = 0;
    }

    return ++this.count;
}
```
- example usage
```shell
...
var self = this,
    href   = url.href,
    method = url.method,
    params = url.params;

this.requests++;
this.queue.requests++;
this.queue.push();

request(url.method,
        url,
        url.params,
        opts,
        tries,
        function (err, res, data) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
