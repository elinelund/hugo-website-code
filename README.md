# hugo-website-code

This is the Hugo website for Eline Lund. 

## Getting Started

These instructions will get you a copy of the website up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Install brew on your computer. 

Via the terminal type:

```
Give examples
```

### Installing Hugo

A step by step series of examples that tell you how to get a development env running

Install Hugo
```
brew install hugo
```

### Getting the website content

Then pull the content of the website to your machine
```
git clone https://github.com/elinelund/hugo-website-code.git
```


## Run the website locally

To run the website on your machine simply run:

```
hugo server
```

## To deploy the website to GitHub

Delete the public folder (to make sure the latest changes are added)

```
rm -rf public
```
and rebuild the website
```
hugo 
```
This will create a new public folder wich you can push to your github.io repository



## Built With

* [Hugo](https://gohugo.io/) - The website generator 
* [Hugo-icon](https://themes.gohugo.io/hugo-icon/) - The Hugo-icon theme

## Authors

* **Sam Heyman** - *Initial work* - [Sam Heyman](https://github.com/SamHeyman)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

