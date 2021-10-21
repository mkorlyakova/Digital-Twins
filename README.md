# Digital-Twins

Обучение нейросетевой модели для системы управления парогенератора

Входы: 
  - результаты измерений в отдельных узлах стенда температуры и давления пара
  - управляющие воздействия извне
  - внешняя температура
Выход: предсказание поведения системы в следующий момент времени

Методика:
  - обучение LSTM сети
  - контроль переобучения (лучше более грубая система)
  - проверка на режимах за границами обучения


Результат:
 Brynza A.A., Korlyakova M.O. Approach to forecasting behavior of dynamic system beyond borders of education// Studies in computational intelligence. 2020. Т. 856. С. 367-374. 
 Test results of the digital active system for dynamic forces reduction and pressure pulsations damping in pipeline compensators 	Kiryukhin A. V; Milman O.O.; Ptakhin A.V.; Korljakova M.O. 	International Journal of Civil Engineering and Technology 	Journal Article 	09766308 	2018 	2 -s2.0- 85055837130
