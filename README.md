# Vala solution to Diverse Seminar 2017 Homework

- Language used: ![Vala](https://wiki.gnome.org/Projects/Vala/)
- Library used: ![valum](https://github.com/valum-framework/valum)

## Build

```bash
$ mkdir build && cd build
$ meson ..
$ ninja
```

## Run

From `build`

```bash
$ cd build # if not already in build
./src/diverse-seminar-2017-microservice
```

## Status

For now, just a hello world :)

TODO:
- [ ] login service
	- [ ] post login json, http 200 answer
	- [ ] good login, return json file with token
	- [ ] bad login, return json file with message
	- [ ] (bonus) token time limit
- [ ] compute service
	- [ ] post expression
	- [ ] return result
