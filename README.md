# Testing

Se han creado 10 pruebas correspondientes a cada uno de los casos de prueba. Cada prueba ejecuta diferentes escenarios dependiendo del caso.

Los archivos se nombran de la siguiente manera:

test1RegistervalidNameEmailPassword.cy
test2Namefield.cy
test3EmailField.cy
test4PasswordField.cy
test5SubmitNoFullFields.cy
test6PasswordDoNotMatch.cy
test7Login.cy
test8LoginNoFullFilds.cy
test9UserNameInHome.cy
test10LogOut.cy
Para ejecutar estos tests, es necesario tener Cypress instalado en el proyecto. Hay dos opciones disponibles:

La primera opción permite visualizar los resultados desde la terminal de Visual Studio Code. Ejecuta el comando "npx cypress run". Después de unos minutos, se mostrará el resultado de todos los tests.

La segunda opción es ejecutar los tests de manera que se puedan visualizar los resultados en un navegador. Usa el comando "npx cypress open".
