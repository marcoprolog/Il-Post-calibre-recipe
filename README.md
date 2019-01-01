# Il-Post-calibre-recipe
Calibre recipe to download articles from Il Post (Italian newspaper) so they are easily readable on e-readers

## How to use
Download and load in Calibre:
1. "Download the 'Il Post.recipe' file"
1. "Add or edit custom news source"
2. "Load recipe from file"
3. "Open the downloaded file"
4. (Optional) Change configuration, see next section
4. Click save

## Customization
* You can customize what sections to download by commenting (add # in front) the sources you are not interested in. For example, in this case "Prima pagina" is enabled, and "Mondo" is disabled

```python
sections = [
    ("Prima Pagina", "https://www.ilpost.it/"), 
    #("Mondo", "https://www.ilpost.it/mondo/"), 
	...
```

* You can choose if you want images to be converted in greyscale or not (by default yes) by changing the line
```python
convert_to_grayscale = True
```
to
```python
convert_to_grayscale = False
```