# Pre Rendering in next js

pre means(phala) and rendering means (converting java script in to html) . Next js phala sa html pages ko render kr

 liata hai jab user ata ha to us ko w8 ni krna prta immedietly us ko page pa para content mil jata hai. jis ki waja sa 

 seo bht achi rahti ha 
 ## IF WE USE ONLY RECT 
  Agr  hum react  ko use krta hai without next to us ma pre rendering ni ha sara pages client side pa  load ho gai jis 
  
ki waja sa  performance bad ho gi or seo to na hona ka baraber ha

# Hydration

html ,css or java combine use hoti hai har website ma. jaisa hi java code run hota hai page interactive ho jata hai isa  

hydration khata hai 

# Two form of  Pre Rendering

## Static Generation 

static means (fixed). mtlb ya aik hi dfa render ho ga on built time.jab bhi kisi user ki request ay gi to phala sa data 

para ho  ga. static hum us wqt use krta hai jab data ma koi change na kra ho

## Server Generation 
 page har request pa load ho ga . client side pa load nahi ho ga server side pa load ho ga (ku ka data change ho raha ho ga). 
 
 is ko hum us wqt use krta hai jab hamia pata ho ka data har request pa change ho ga

 ## per page base

 Next ka feature ha ka hum us ko ya bta skta hai ka hum na kis page ko static or kis page ko server side ma run krna hai

 ## Static Generation With out data

 By default next js har page ko static generate krti hai . next .js assume krti hai ka baher sa koi data ni ay ga. laiken agr humai baher sa data chiyai to phit hum kiya kra?
 
static generation with data allow krta ha ka hum baher sa data la ska. wo data hum api sa bhi la skta hai.

#### generating static page with externel data

agr hum na static page banana hai or us ma externel data lai ka ana hai to hum page ka component pa 

## get static prop()

ka function use kra gai.is function sa next ko samgh a jata hai ka page static generate ho ga laiken us ma externel data 

ki zarrort bhi ho gi.jo hum function ko use kr ka fetch(data ko la kr ana ) kr skta hai

