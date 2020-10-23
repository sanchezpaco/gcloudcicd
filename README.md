# Google Cloud CI/CD 

Test project for learning how to work with Google Cloud Build and Google Cloud Run

## Getting Started

Just run:

```
docker build . -t gcloudcicd 
docker run -d -p 80:8080 gcloudcicd
```

Then you'll have available the website at localhost


### Prerequisites

Docker!


## Deployment

This automatically builds and deploys once is merged in main branch using Google Cloud Build

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Paco Sanchez** - [Paco_S](https://twitter.com/Paco_S)

## License

This project is licensed under the GNU General Public License - see the [LICENSE.md](LICENSE.md) file for details