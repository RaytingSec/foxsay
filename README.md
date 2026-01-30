Foxsay
==============================

Fox cowfiles to extend your cowsay library of animals and friends to include foxes.


Usage
----------

### Installing

Install and test:
```bash
sudo cp $cowsay_file /usr/share/cowsay/cows/
echo "Hello!" | cowsay -f $cowsay_file
```

### Development

Provides lower latency feedback, useful for viewing "live" updates of cow file

```bash
cowsay_file=./fox.cow
while true; do
    bash -c "echo \"\`date -Iseconds\`\" | cowsay -f ./${cowsay_file}";
    sleep 1;
done
```


Cowfiles
----------

### Fox

Simple ASCII fox in sitting position.

![fox_example.png](/readme/fox_example.png)

### Rayting

Colored version of the fox named Rayting with silver fox fur pattern and blue accents.

Color is added with ANSI 256 color codes [(Wikipedia reference)](https://en.wikipedia.org/wiki/ANSI_escape_code#Colors) 

![rayting_example.png](/readme/rayting_example.png)
