# STM32F411_Project

---

## Hardware
![STM32F411_블럭도](img/F1.PNG "STM32F411_블럭도")
![STM32F411_블럭도](img/F2.PNG "STM32F411_블럭도")
![STM32F411_블럭도](img/F3.PNG "STM32F411_블럭도")
![STM32F411_블럭도](img/F4.PNG "STM32F411_블럭도")


---

## Firmware

- Pinout & Configuration
![STM32F411 Setting](img/001.png "STM32F411 Setting")
- Clock Configuration
![STM32F411 Setting](img/002.png "STM32F411 Setting")
- Project manager
![STM32F411 Setting](img/003.png "STM32F411 Setting")

---
```
/* Infinite loop */
  /* USER CODE BEGIN WHILE */
  while (1)
  {
    /* USER CODE END WHILE */

    /* USER CODE BEGIN 3 */
  }
  /* USER CODE END 3 */
}
```
---
- LD2 1초 Delay
``` /* USER CODE BEGIN WHILE */
  while (1)
  {
    /* USER CODE END WHILE */

    /* USER CODE BEGIN 3 */
	      HAL_GPIO_TogglePin(LD2_GPIO_Port, LD2_Pin);
	      HAL_Delay(1000);
	      /* USER CODE END 3 */
	    }
  }
 ```
--- 
