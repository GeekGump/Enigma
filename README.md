#Enigma machine
(this repositore is writed based on a video by [jadi](https://github.com/razyar/jadijadi) on youtube)

# requirements:

```
python2
pickle
```

# Generate new rotor settings:
my settings are setted in ``` rotor_state.rotor ``` but if you want your new rotors settings just run:
```bash
python rotor_generator.py
```
if you use this for a chat or anything else you need to send your rotor settings to your client.

# Run enigma: 
first enter your text in:
[ln]:42 -> ```python plain = "anything" ```
and run ```bash python enigma.py``` output for "anything" with my settings will be: "pbqdwlqk"
and for decode this "pbqdwlqk" just change the ```python plain = "pbqdwlqk"``` to "anything"

have problem? contact: [razyar](https://khoderazyar.ir)
