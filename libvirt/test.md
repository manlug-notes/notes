### Change the Memory of a Virtual Machine
Change the memory of a running instance, it can only set to the max memory limit
```python
virsh -c qemu:///system setmem --domain centos7 --size 4G --live   # will take affect on an active instance
virsh -c qemu:///system setmem --domain centos7 --size 4G --config # will take affect after next full shutdown</textarea>
```

Increase the Max memory limit
