# Viewsaurus

A Viewsaurus is an interactive tutorial for documentation portals.

[Demo](https://melissakendall.github.io/viewsaurus/index.html)

# Getting Started

## Before You Begin

* Install [Node.js](https://nodejs.org/en/).

## Steps

1. Fork this repo
2. Clone your forked repo - `git clone git@github.com:{yourusername}/viewsaurus.git`
3. Open your directory - `cd viewsaurus`
4. Install [viewsaurus](https://www.npmjs.com/package/viewsaurus) globally - `npm install viewsaurus -g`
5. Start the tutorial locally - `saurus author`
6. View the tutorial at [http://localhost:8080](http://localhost:8080)

## Making Your Own

To make your own tutorial, follow these instructions.

1. Check out master - `git checkout master`
2. Edit `tutorial/config.json`
3. Start the tutorial from scratch - `saurus new`
4. Start the tutorial locally - `saurus author`
5. View the tutorial at [http://localhost:8080](http://localhost:8080)
6. Make changes to `tutorial/index.jade` as desired

---

## Resources

* [Installing Node.js](https://docs.npmjs.com/getting-started/installing-node)
* [Jade Template Engine](http://jade-lang.com/)
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [Viewsaurus](https://www.npmjs.com/package/viewsaurus)

## License

MIT