# Registrodevf-o-algo-as-
voltea una cadena de caracteres y te dice la frecuencia con que aparece el caracter 'e'

public String reves(String nombre){ 
  char a[ ]=new char[100]();      
  char b[ ]=new char[100]();             
  b=nombre.toCharArray();                    
  for(int i=0;i<nombre.length;i++){      
     a[nombre.length-i]=b[i]; 
     if(b[i].equals('e'))                                                                                             
      cont++;  
}                           
return a.toString()+" Frecuencia de 'e': "+cont+ " veces.";                                                                                 ;        
}    
