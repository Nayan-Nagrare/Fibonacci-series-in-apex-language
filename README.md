# Fibonacci-series-in-apex-language

Integer beforeprevious=0;
Integer previous=1;
Integer current;
system.debug(beforeprevious);
system.debug(previous);

Integer i=0;


while(i<18)
{
    current=beforeprevious+previous;
    system.debug(current);
    beforeprevious=previous;
    previous=current;
    i++;
}
