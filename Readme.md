#Para comprobar si el Podspec es correcto.

pod spec lint YourPod.podspec --verbose

#Para subirlo a CocoaPods

pod trunk register <YUOREMAIL> ‘<YOUR NAME>’ — description=’owner from macbook pro’

#Hacer Click en el email que hemos recibido y a continuación:

pod trunk push YourPod.podspec


#Para hacerlo en Private

#Crear un tag 

git tag 0.1

#Pushearlo

git push -u origin —- tags
o
git push -u origin master --tags

#Añadimos nuestro repositorio.

pod repo add <yourSpecsName> <yourPodRepoDirectory>
e.g. 
pod repo add MyFirstPod https://github.com/pabsanmez/MyFirstPod.git


#Validamos

pod repo push myspec MOHUD.podspec — verbose

#Añadimos el source en el podfile que vayamos a utilizar nuestro pod.

source "https://bitbucket.org/moath_torch/mospecs/"



