Este proyecto se enfoca en el diseño e implementación de un sistema de control de nivel de líquido en un tanque, utilizando un controlador de tipo ON-OFF. La configuración del sistema, basada en un PLC, permite que el operador supervise y ajuste los niveles desde dos puntos principales: una HMI local y un sistema SCADA implementado en la plataforma WINCC®. Este sistema de control no solo regula el nivel del líquido, sino que también incorpora importantes medidas de seguridad mediante sensores de nivel alto (LEH) y nivel bajo (LEL), los cuales aseguran la operación en condiciones óptimas, evitando la activación de la bomba en escenarios peligrosos o no deseados. Además, el sistema registra en una base de datos local y en la nube datos críticos como las revoluciones de un variador de velocidad, proporcionando una visibilidad integral del sistema en funcionamiento y permitiendo un almacenamiento seguro de los datos para análisis futuros y optimización continua. 

![image](https://github.com/user-attachments/assets/dd11c94a-191a-4b97-b3fa-066f7858262c)

La interfaz del operador fue desarrollada en dos sistemas de supervisión: un HMI local con un pantalla KTP700 Basic y un sistema SCADA en WINCC®. Ambos sistemas incluyen un deslizador y una caja de texto, permitiendo al operador definir de manera precisa el nivel de referencia deseado. Estos elementos fueron diseñados para ser intuitivos y fáciles de usar, proporcionando una experiencia de usuario fluida y directa. Además, se añadieron botones de start, stop y paro de emergencia tanto en la interfaz física como en la interfaz de supervisión, asegurando que el operador tuviera un control total sobre el sistema en cualquier momento. La comunicación entre el PLC y los sistemas de supervisión se configuró para que cualquier cambio en el nivel de referencia o en los estados de los botones fuera inmediatamente reflejado en ambas plataformas. 

![image](https://github.com/user-attachments/assets/02e08f05-36a3-4521-b8ab-f9a06cbdd19b)
variador:


![image](https://github.com/user-attachments/assets/3d5445ec-729d-4989-85c9-84f1a34082b2)

servomotor:

![image](https://github.com/user-attachments/assets/f1f5461a-1306-4482-b169-80fe2ebc12e8)

Parametrización:

![image](https://github.com/user-attachments/assets/7d6bb50c-7327-46ab-b624-eed3f9bfbf08)
Objeto tecnologico variador:

 ![image](https://github.com/user-attachments/assets/91f92590-f0f9-43fd-9ce3-cee3a5e63382)

 
 ![image](https://github.com/user-attachments/assets/315c5b5f-f239-4888-9d8f-f21d6680389e)



 ![image](https://github.com/user-attachments/assets/a46084f3-d898-4e6e-81b5-47b3052548e8)



 comunicacion profinet:

 ![image](https://github.com/user-attachments/assets/dfea40cb-e75a-4aa3-8e9b-7394d375cf29)







