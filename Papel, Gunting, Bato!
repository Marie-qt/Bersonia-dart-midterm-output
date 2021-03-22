import 'dart:math';
import 'dart:io';


void main() {

int botscore=0;
int yourscore=0;
int round= 1;

for( var i = 5; i >= 1; i-- )

{

  Random random = new Random();
  int randomNumber = random.nextInt(3) +(1); 
  
    print ('ROUND $round');
    print('Gunting, Papel,Bato.');
    print ('What is your pick?');

String pambato= stdin.readLineSync();

print ('------------------');


if(pambato == 'bato'|| pambato== 'Bato')
{
if(randomNumber==2)
{
print( '$pambato vs Gunting ');
print ('You Win');
yourscore = yourscore+1;
}
else if(randomNumber==0)
{
print( '$pambato vs Bato ');
print ('Tie');
}
else
{
print( '$pambato vs Papel ');
print ('You Lose');
botscore= botscore+1;
}
}


if(pambato == 'gunting'|| pambato== 'Gunting')
{
if(randomNumber==2)
{
print( '$pambato vs Gunting ');
print ('Tie');
}
else if(randomNumber==0)
{
print( '$pambato vs Bato ');
print ('You Lose');
botscore= botscore+1;
}
else
{
print( '$pambato vs Papel ');
print ('You Win');
yourscore= yourscore+1;
}
}


if(pambato == 'papel'|| pambato== 'Papel')
{
if(randomNumber==2)
{
print( '$pambato vs Gunting ');
print ('You Lose');
botscore= botscore+1;
}
else if(randomNumber==0)
{
print( '$pambato vs Bato ');
print ('You Win');
yourscore= yourscore+1;
}
else
{
print( '$pambato vs Papel ');
print ('Tie ');
}
}


round=round+1;

print ('------------------');
print('Bot score: $botscore' );
print('Your score: $yourscore' );
print ('''*****************


''');


}
}
