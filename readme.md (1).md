# Entorno virtual para ciencia de datos
### Voy a explicar como configurar el entorno virtual que usaremos para la actividad.
 # Descarga de Anaconda
 ###  En primer lugar iremos al sitio web de [anaconda](https://www.anaconda.com/download) descargamos el programa y lo instalamos en nuestro ordenador.
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182367419893817424/image.png?ex=65847078&is=6571fb78&hm=f9f329c6a9bd184af322ddef94e7a86f9a0b87bc29a1794a689bf0a70ad42033&)
 # Creacion de nuestro entorno virtual
 ### Buscamos **anaconda prompt** en la barra de búsqueda de windows y lo inciamos.
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182379336569995375/image.png?ex=65847b91&is=65720691&hm=5a5f9973d94a697540f92492b83e2b0271cabe6cf0709a5b23ce6182248efcb0&)
 
 ### A continuacion crearemos el nuevo entorno virtual que utilizará python 3.10, con el comando `conda create --name "nombre del entorno" python=3.10`
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182389899178016872/image.png?ex=65848567&is=65721067&hm=927390aff4c989c803a7c3fc5a4ccf473ac7e72aaa2e795fb76da310f3a874ba&)
 
 # Instalar los paquetes deseados en el entorno virtual.
 
### En este paso añadiremos los siguientes paquetes para nuestro entorno: Jupyter, Numpy, Pandas, Matplolib, Seaborn, Scikitlearn, Tensorflow y Scrapy.
 
 * En primer lugar pasaremos del entorno base de Anaconda al nuevo entorno que hemos creado con el comando ``conda activate "nombre del entorno"``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182392569565548554/image.png?ex=658487e4&is=657212e4&hm=8639a8172f085e401812d71a5af6d1a681530fec117fd9d6e73b25c63e4589cc&)
 
 * Ahora procederemos a instalar los paquetes en primer lugar para Jupyter utilizaremos el comando ``pip install notebook``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182399524631760977/image.png?ex=65848e5e&is=6572195e&hm=5b164b03c6f8cae8788343f0eb2a407c30288e8c749b4aae3e461ed2ae7e8329&)
 
* Para numpy usaremos el comando ``pip install numpy``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182399822012092426/image.png?ex=65848ea5&is=657219a5&hm=799a0c4413156503aecfb65df33c26499c2bbfb0b8028d67134f6cbb6764f71f&)
 
* Para pandas usaremos el comando ``pip install pandas``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182400287126859917/image.png?ex=65848f14&is=65721a14&hm=218318280395e2d8bbf6d18f7639be93ca30d32bda8bb2c44fdba1edde5c3ebb&)
 
* Para matplilib usamos el comando ``pip install -U matplotlib``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182401072376070154/image.png?ex=65848fcf&is=65721acf&hm=428457c333fced1524c78ba11ed8903b6e24557e9ef85525c43596dc89e8e43b&)
 
* Para seaborn usamos el comando ``pip install seaborn[stats]``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182401462249205910/image.png?ex=6584902c&is=65721b2c&hm=2ca0e86457a318a15571833a4e5bb76f50608fa2fb54f867d8b4fa00d904cf0e&)
 
* Para scikitlearn usamos el comando ``pip install -U scikit-learn``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182401880488419479/image.png?ex=65849090&is=65721b90&hm=23f207d04c5265cd25a9ea6fa3664140ee947f6492c2728fdfdd1d0233127f54&)
 
* Para Tensorflow primero instalaremos cudatoolkit y cdnn con el comado ``conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0.´´ para que tensor flow pueda trabajar con nuestra GPU y no solo con nuestra CPU (**Ignorar este paso si no se dispone de una gráfica NVIDIA con CUDA 3.5, 5.0, 6.0, 7.0, 7.5, 8.0 o superiores**)
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182402621949095966/image.png?ex=65849141&is=65721c41&hm=ada2ee977411e32a191d60e6706b82ac15f4a0fd437583f6f595c8bbc8b42478&)
 
* A continuacion instalaremos tensorflow 2.10 con el comando ``pip instal tensor flow==2.10``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182410522692436009/image.png?ex=6584989c&is=6572239c&hm=fc9cc9413463ee5727236ccf3c99b3688529670ca3c3d591071442359f315e81&)
 
 * Por ultimo instalamos scrapy con el comando ``pip install scrapy``
 
 ![image](https://cdn.discordapp.com/attachments/286242433912537088/1182410954475044894/image.png?ex=65849903&is=65722403&hm=6a315c77372f3543863c814e5a40ab1049b35f427b0772c1d876c50b541137bb&)
