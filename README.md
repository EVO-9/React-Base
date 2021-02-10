# React

## Create a new React App
Make sure you are in your apps parent folder i.e. the folder you are installing all your app into.
### Create a new React App
```
npx create-react-app <app-name>
```
(Change <app-name> to match you app name)
### Create a new React App with Typescript
```
npx create-react-app dojo-blog-airtable --template typescript
```
(Change <app-name> to match you app name)

## Start a development server
```
npm run start
```

# NOTES

## Folder Structure
	* node_modules
		* All the dependencies live
		* If you delete this, all you need to do is go to your app directory and type `npm install`  and it will install all the packages.
	* public
		* All the public files that are public to the browser will live in here.
		* This is the one html file that is served to the browser and all our react code will be injected into that file.
	* src
		* 99% of the code we write will go in here
