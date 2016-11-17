# drf-angular-user-system
A user management system, consisting of a RESTful Django (DRF) server and an AngularJS SPA client.

It is meant to be used as a backbone for any DRF + Angular project requiring user authentication, including social authentication.

## Structure

### Client

Client is provided as an NPM package. Its dependencies are:

* Angular
* Bootstrap

### Server

The main functionality is provided by the Django app `usersystem`.

Server requirements include:

* Django
* Django Rest Framework

You can install the requirements from `requirements.txt` (Preferably using `virtualenv`)

## License

Copyright 2016  Simo Iliev

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
