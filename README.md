## Quick start

### Vagrant Option
1. Clone this repo using `git clone https://github.com/jcarroll2007/vagrant-react.git`
2. Move to the appropriate directory: `cd vagrant-react`.<br />
3. Run `vagrant up` in order to create the virutal machine.<br />
4. Run `vagrant ssh` to ssh into the machine.
5. Run `cd /vagrant/ && npm run start` to begin the development server.
6. Navigate to <a href="http://localhost:8888/">localhost:8888</a> to connect to the server.

### Local Development
For this option you must have node and npm installed on your machine.

1. Run `npm install` to install node modules
2. Run `npm run postsetup` to create necessary files for build config.
3. Run `npm run start` to start the development server and navigate to <a href="http://localhost:3000/">localhost:3000</a> in your browser.

## License

This project is licensed under the MIT license, Copyright (c) 2017 Maximilian
Stoiber. For more information see `LICENSE.md`.
