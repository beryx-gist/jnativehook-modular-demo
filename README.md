# jnativehook-modular-demo

This project shows how to create a custom runtime image of a modular application that uses [jnativehook](https://github.com/kwhat/jnativehook).


## Build

<details open>
<summary>Windows</summary>

```shell
gradlew build jlink jpackage
```

</details>
<details open>
<summary>Linux</summary>

```shell
./gradlew build jlink jpackage
```

</details>

## Execute custom runtime image

<details open>
<summary>Windows</summary>

```shell
build\image\bin\jnativehook-modular-demo.bat
```

</details>
<details open>
<summary>Linux</summary>

```shell
./build/image/bin/jnativehook-modular-demo
```

</details>

## Install application package

<details open>
<summary>Windows</summary>

```shell
build\jpackage\jnativehook-modular-demo-1.0.0.msi
```

</details>
<details open>
<summary>Linux</summary>

```shell
sudo apt-get update && sudo apt install ./build/jpackage/jnativehook-modular-demo_1.0.0-1_amd64.deb
```

</details>

You can also download the packages [created by the GitHub Actions](https://github.com/beryx-gist/jnativehook-modular-demo/actions/runs/3777695543#artifacts).
