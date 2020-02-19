#Android Studio: /dev/kvm device permission denied

Execute o seguinte comando no terminal:

```
sudo apt install qemu-kvm
```

Adicione seu usuário ao grupo do KVM:

```
sudo adduser <seu usuário> kvm
```
Se ainda estiver mostrando permissão negada:
```
sudo chown <seu usuário> /dev/kvm
```
