## Laravel 5.4 with Semantic UI pre-configured.

### Quick start

#### 1. Install semantic

Semantic is configured in semantic.json. Choose to use existing configuration when prompted.

`npm install semantic`

#### 2. Build semantic by running

`cd resources/semantic`

`gulp build`

#### 3. Use Laravel mix to output the files to public directory.

Make sure you have webpack set up according to Laravel docs.

CD back to project root from the semantic director:

`cd ../..`

Then execute webpack

`npm run dev`

#### Check for your files

`public/css/all.css` and `public/js/app.js` comes with the repository but they are regenerated by Laravel mix.

### Notes

The default `resources/assets/sass/app.scss` has been commented out as it contains bootstrap. You can use this file for your own css or remove it from `webpack.mix.js`.