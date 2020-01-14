
- [INIT](#init)
- [gdzie zaczac](#gdzie-zaczac)
- [komuna](#komuna)
- [kursy](#kursy)
- [trendy](#trendy)
- [zen of python](#zen-of-python)
- [COMMIT](#COMMIT)

<br><br/>
<br><br/>


# INIT

Jako wasza baze, powinninscie MOCNO przestudiowac 

[  Stack Overflow Developer Survey Results
2019 ](https://insights.stackoverflow.com/survey/2019 ) - prawie 100 tys developerow (robia co roku nowa)


Zobaczycie tam informacje na temat zarobkow, trendow, popularnosci jezykow, technologii, narzedzi, 
ale tez  na przyklad kontekst na zwiazany z tym jakie jezyki / technologie sa lubiane przez ludzi w praktyce   - bardzo pomocne !  

Jako ze uwielbiam Pythona fragment z poczatku ankiety: 

“ Python, the fastest-growing major programming language (...) standing as the second most loved language (...)” 


Z mojej perspektywy, Python jest bardzo szybki do zrozumienia, nie potrzeba ogromnej ilosci czasu zeby zaczac czuc sie z nim swobodnie, jest to jezyk general-puropose - czyli o bardzo szerokim zastosowaniu. 

Jest tez jezykiem ktorego funkcyjne czesci kodu sa odzielone od siebie tab(ami) - (4x spacje / whitespace)  - czyli jego struktura / syntax od poczatku wymusza bardzo czytelne przejrzyste pisanie kodu

Jesli zdecydowalibyscie sie na Pythona to dobrym pomyslem jest zaczac od [ Anacondy]( https://www.anaconda.com/distribution/ ) - dystrybucji pythona 3.7

Anaconda uzywana jest glownie w data science i machine learnig, ale jest to dobry poczatek dla kazdego poniewaz macie od razu zainstalowane wiele packages / bibliotek pythona ktore sa potrzebne kazdemy kto z nim pracuje, bez pozniejszej potrzeby manualnego instalowanie pojedynczych pakietow - takze ulatwiony start 


# gdzie zaczac 

Jezyki front end typu java script (js), html, css sa coraz bardziej zautomatyzowane i miel platne

Polecam jezyki general purpose, ktore moga byc uzyte do pisania zarowno webbowych aplikacji jak i automatyzowania back end / infrastruktury  

Na wstepie bardzo wam sie przyda:

- linux

   - podstawowe komendy mozecie testowac na Mac OS w terminalu lub przez [iterm2]( https://iterm2.com/ ) (np. ls, mkdir, touch, cp, mv, cat, grep, vi,  etc...)
   - komercyjnie / w firmach jest bardzo popularna darmowa dystrybucja RedHata - Centos - dlatego polecam zabawy z ta wersja Linuxa
   - ciekawa i tania opcja moze byc zainstalowanie Centos na Raspbery Pi (headless installation)
   - jesli juz znudzicie sie bialo/czarnym ekranem terminala - czas na [ oh my z shell !!! ](https://ohmyz.sh/ ) :)

- bash / shell programming

   - minimalna wiedza rowniez czesto przydatna

- jeden jezyk typu genreal purpose (Python, Go, C, Ruby etc...)
   - jako edytor / narzedzie do pisania zdecydowanie polecam [ VScode ]( https://code.visualstudio.com/ )
   - piszcie [ ludzio przyjaznie ](https://pythonforbiologists.com/3-steps-to-readable-code) i [ zwiezle ]( https://www.codementor.io/@joshuaaroke/dry-code-vs-wet-code-89xjwv11w ) a wasz kod bedzie jednoczesnie dobra dokumentacja
 
- regex

   - podsatwy zawsze beda pomocne  

- git 

- automatyzacja - Everything as Code - EaC :) 



Po jakims czasie mozecie zaczac sie inetresowac tematem:
- Devops
   - narzedziach i techologie stosowane w DevOps - toolset

      - docker, kubernetes, CICD - continuous integration continuous deployment, jenkins, gitlab CI, microservices,API, narzedzia Hashicorp, Ansible i wiele innych
      
- Cloud 
   - [ AWS ](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc) (amazon) 
   
   albo 
   
  - [GCP]( https://cloud.google.com/free/ ) (google)
   
- w obu przypadkach AWS / GCP - kiedy sie zapisujecie macie pierwszy rok za darmo, mozecie duzo testowac przez zabawe 

# komuna

[ meetup ](https://www.meetup.com/)

wpisujcie kluczowe hasla typu python, cloud, AWS, devops etc i zobaczycie ze duzo sie moze dziac tam gdzie jestescie 





# kursy
Sporo uzywalem 

- [ linuxacademy ]( https://linuxacademy.com/ ) 
   - miesiczna subskrypcja i dostep do wszystkich kursow - bardzo profesjonalne kursy Linux, Cloud, Narzedzia etc.
   - kursy bardzo zblizone do prawdziwych firmowych 
- [ udemy ]( https://www.udemy.com/ ) 
   - placisz za indywidualny kurs, ogromny wybor, duzo ocen kursow - ratingow, 
   - nie placcie wiecej niz 10-20 Euro za kurs - zawsze czekajcie na promocje przy ktorych przewaznie placicie 10 razy mniej. 
   - jesli kurs wydaje sie drogi - ponad 20 euro - pewnie poza okresem romocyjnym, odczekajcie tydzien, dwa   
- [ codecademy ]( https://www.codecademy.com/ ) 
   - darmowe kursy z opcja premium (HTML & CSS, Python, JavaScript, Java, SQL, Bash/Shell, Ruby, C++, R, C#, PHP, Go, Swift)
   - bardzo dobra darmowa opcja, premium bardzo niekonieczne :) 

rzuccie okiem

- [ udacity ]( https://www.udacity.com/ )
- [ cursera ]( https://www.coursera.org/ ) 
- [ pluralsight ]( https://www.pluralsight.com/ ) 

znajdy agi :) 

- [ girlsjs ](https://girlsjs.pl/) - js
- [ djangogirls ](https://djangogirls.org/) - python 



# trendy

- private cloud
   - OpenStack
   
- public cloud
   - AWS, GCP, Azure
   
- DevOps
   - ogromne na calym swiecie migracje aplikacji do cloud
   - containerization - docke, kubernetes, packer
   - microservices
   - lambdas
   - CICD pipelines - GitLab CI i Jenkins
   - automatuzacja / Everything as Code - EaC:)  
   - Infrustructure as Code - Ansible, Terraform

- big data
- data science
- machine learning 
- robotyka 


# zen of python

```python 

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```



# COMMIT


#### z czym moglbym wam wiecej pomoc 


```python
python
js
linux
Infrastructure as Code
Ansible
Terraform
cloud - AWS, OpenStack
network

mam sporo kursow na udemy (Ansible, Linux, Git, , Python 3, DevOps, Aws,GCP, Jenkins,Gitlab CI, Terraform, Docker, Kubernetes)
dajcie cynk jesli bylibyscie zainteresowani
```



   














