# Projekt 06 Island

Vyberte si jakou úroveň zvolíte (psaní vlastního HTML se ovšem nevyhnete):

1. [Hard](/zadani/hard/)
1. [Soft](/zadani/soft/)

Ve složce [zadani](/zadani/) jsou obrázky s předlohou. Na [záznamu obrazovky](https://drive.google.com/file/d/1SH_SiQlDxO-iSC0XqyFwEfhxS3Or5YFR/view?usp=sharing) uvidíte chování fotogalerie. Kdyby se vám otvíralo malé, nejprve si ho stáhněte a pak otevřete v Chromu.

Své řešení opět uložte do kořenového adresáře projektu (tedy mimo složku `/zadani`).

/* Container needed to position the overlay. Adjust the width as needed */
.container {
    position: relative;
    width: 50%;
    max-width: 300px;
  }
  
  /* Make the image to responsive */
  .image {
    display: block;
    width: 100%;
    height: auto;
  }
  
  /* The overlay effect - lays on top of the container and over the image */
  .overlay {
    position: absolute;
    bottom: 0;
    background: rgb(0, 0, 0);
    background: rgba(0, 0, 0, 0.5); /* Black see-through */
    color: #f1f1f1;
    width: 100%;
    transition: .5s ease;
    opacity:0;
    color: white;
    font-size: 20px;
    padding: 20px;
    text-align: center;
  }
  
  /* When you mouse over the container, fade in the overlay title */
  .container:hover .overlay {
    opacity: 1;
  }
