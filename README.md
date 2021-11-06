DESDE nginx: último

COPIA index.html / usr / share / nginx / html
COPIA arleth.png / usr / share / nginx / html

EXPONER 80 443 	

CMD [ "nginx" , "-g" , "demonio desactivado;" ]
