#include <iostream>
using namespace std;
int main()
{
  char q1;
  char q2;
  char q3;
  char q4;
  char q5;
    string user;
    string pj;
   cout << "Bienvenido usuario a \"Afinidad en 5 pasos\"\nIntroduce tu nombre:" << endl;
   cin>>user;
   cout<<"Ahora, introduce el nombre de la persona con la que vas a interactuar"<<endl;
   cin>>pj;
   int value = 0;
   cout<<"Gracias, disfruta de la experiencia"<<endl; 
 do{
cout<<"En una tarde normal como la de todos los dias, "<< user<<" ve a alguien sentado en una banca, leyendo un libro. "<< user<<" se acerca y dice:\na)¡Hola! Ese libro se ve interesante. ¿De qué trata?\nb)Perdón, ¿sabes a qué hora empieza el evento?\nc)Vaya, no sabía que todavía había gente que leía libros en lugar de mirar el celular.\n\n"<<endl;

cin>>q1;
if (q1 >= 'A' && q1 <= 'Z') {
        q1 = q1 + 32;}  
if(q1=='a'){value++;}
else if(q1=='b'){value = value; }
else if(q1=='c'){value--;}
     
 } while (q1!='a' && q1!='b' && q1!='c');

do{cout<<"La persona responde con una sonrisa y se presenta, "<<pj<<" menciona que le encantan las historias de misterio. ¿Cómo "<<user<<" continúa la conversación?\na)¡Qué coincidencia! También me gustan. ¿Tienes algún libro favorito que me recomiendes? \nb)Interesante. Yo suelo leer otras cosas, pero suena bien.\nc)Ah, nunca he leído un libro de misterio. No creo que sean muy entretenidos.\n\n"<<endl;

cin>>q2;
if (q2 >= 'A' && q2 <= 'Z') {
        q2 = q2 + 32;}  
if(q2=='a'){value++;}
else if(q2=='b'){value = value; }
else if(q2=='c'){value--;}}while (q2!='a' && q2!='b' && q2!='c');

do{cout<<"Mientras hablan, accidentalmente empujas su botella de agua y la tiras al suelo. ¿Cómo reacciona " << user << "?\na)¡Lo siento mucho! Déjame comprarte otra para compensarlo.\nb)Uy, fue mi culpa. Perdón.\nc)Bah, solo es agua. Se seca rápido.\n\n"<<endl;

cin>>q3;
if (q3 >= 'A' && q3 <= 'Z') {
        q3 = q3 + 32;}  
if(q3=='a'){value++;}
else if(q3=='b'){value = value; }
else if(q3=='c'){value--;}} while (q3!='a'&& q3!='b' && q3!='c');

do{cout<<pj << " menciona que está emocionado/a por el evento porque ha estado esperando mucho tiempo por él. ¿Qué dice " << user << "?\na)¡Eso es genial! Se nota que realmente te importa. Espero que lo disfrutes mucho.\nb)Bueno, parece que será interesante. A ver qué tal está.\nc)No entiendo por qué tanta emoción. No parece gran cosa.\n\n"<<endl;

cin>>q4;
if (q4 >= 'A' && q4 <= 'Z') {
        q4 = q4 + 32;}  
if(q4=='a'){value++;}
else if(q4=='b'){value = value; }
else if(q4=='c'){value--;}} while (q4!='a'&& q4!='b' && q4!='c');

do{cout<<"El evento ha terminado y es momento de irse. ¿Qué hace " << user << "?\na)Me encantó hablar contigo. ¿Te gustaría que siguiéramos en contacto?\nb)Bueno, fue un gusto conocerte. Que tengas buen día.\nc)En fin, nos vemos… o no.\n\n"<<endl;

cin>>q5;
if (q5 >= 'A' && q5 <= 'Z') {
        q5 = q5 + 32;}  
if(q5=='a'){value++;}
else if(q5=='b'){value = value; }
else if(q5=='c'){value--;
    cout<<"Que respuesta nonchalant,\n\n\n"<<endl;
}} while (q5!='a'&& q5!='b' && q5!='c');

if (value<=5 && value>3){
    cout<<"Después de la conversación, tu y " << pj << " intercambian números y continúan hablando con entusiasmo. En los días siguientes, descubren que tienen mucho en común y comienzan a pasar más tiempo juntos. Con el tiempo, su relación se fortalece, y lo que comenzó como un encuentro casual se convierte en una amistad (o algo más) increíblemente especial. ¡Parece que encontraste a alguien realmente importante en tu vida!"<<endl;
} else if (value<=3 && value>=1){
    cout<<"Al final del evento, " << pj << " te sonríe y dice que fue genial conocerte. Aunque aún no son cercanos, la interacción fue lo suficientemente buena como para dejar abierta la posibilidad de futuras conversaciones. Tal vez si sigues en contacto, esta amistad pueda crecer con el tiempo"<<endl;
} else if (value==0){
    cout<<"Después del evento, " << pj << " se despide con una sonrisa educada, pero sin mucho interés en seguir la conversación. Fue una charla casual y agradable, pero sin impacto suficiente para que haya una conexión real. Quizás fue solo un encuentro pasajero, sin nada más que recordar"<<endl;
} else if (value<=-1 && value>=-3){
    cout<<"Aunque intentaste interactuar, " << pj << " parece un poco incómodo con algunas de tus respuestas. Al final, se despide rápidamente y se aleja sin mostrar muchas ganas de continuar la conversación. Tal vez la impresión que diste no fue la mejor, y es poco probable que vuelvan a hablar."<<endl;
}  else if (value<-3 && value>=-5){
    cout<<"Respondiste las peores opciones aproposito? "<<" Desde el inicio, tu actitud no ayudó mucho a que la conversación fluyera. " << pj << " parece molesto/a y busca una excusa para irse lo antes posible. Sin despedirse, se pierde entre la multitud del evento, dejando claro que no tiene intención de volver a cruzarse contigo. Definitivamente, no fue tu mejor día..."<<endl;
  }
    return 0;
}
