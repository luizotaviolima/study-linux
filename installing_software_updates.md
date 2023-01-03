# Installing Software and Updates

## .deb
- Para distribuições Debian como Ubuntu e Mint;

## .rpm
- Para distribuições Hat-based como CentOS/RHEL, Fedora e openSUSE;
- RPM = Red Hat Package Manager

deb e rpm são formatos equivalentes;

Se o pacote só existe em um formato, é possível converte-lo para o outros

- rpm to deb

```shell
alien <package-name>.rpm
```
- deb to rpm

```shell
alien -r <package-name>.deb
```

## Updating deb-based Linux
- apt: Linha de comando para atualizar o sistema;

Verificar as atualizações disponíveis
```shell
sudo apt update
```

Realizar as atualizações
```shell
sudo apt upgrade <package-name(optional)>
```

## Installing new software

deb
```shell
sudo apt install <package-name>
```

rpm
```shell
sudo yum install <package-name>
```