# Commandos de git
## Contenido
* ![CNN](https://www.tensorflow.org/tutorials/images/cnn?hl=es-419)
  
## Creación de un repositotio
Para crear un repositorio usar el comando `git init`, enseguida un ejemplo:
```python
class_names = ['airplane', 'automobile', 'bird', 'cat', 'deer',
               'dog', 'frog', 'horse', 'ship', 'truck']

plt.figure(figsize=(10,10))
for i in range(25):
    plt.subplot(5,5,i+1)
    plt.xticks([])
    plt.yticks([])
    plt.grid(False)
    plt.imshow(train_images[i])
    # The CIFAR labels happen to be arrays, 
    # which is why you need the extra index
    plt.xlabel(class_names[train_labels[i][0]])
plt.show()
```
