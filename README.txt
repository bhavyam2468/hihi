# hihi
hi that's me
import java.util.*;
class ttt
{void main()
   { Scanner in=new Scanner(System.in);
        String a="1";
        String b="2";
        String c="3";
        String d="4";
        String e="5";
        String f="6";
        String g="7";
        String h="8";
        String i="9";
        String s="|-----|-----|-----|"+'\n'+"|  "+a+"  |  "+b+"  |  "+c+"  |"+'\n'+"|-----|-----|-----|"+'\n'+"|  "+d+"  |  "+e+"  |  "+f+"  |"+'\n'+"|-----|-----|-----|"+'\n'+"|  "+g+"  |  "+h+"  |  "+i+"  |"+'\n'+"|-----|-----|-----|";
             System.out.println(s); 
              System.out.println("X goes first type the slot number to enter X");
           
        for(int j=1;true;j++)
        {
            System.out.println("Turn of x");
            int n=in.nextInt();
           switch(n)
            {case 1:
                if(a=="1")
                {a="X";}
                else
                {System.out.println("Repeated");}
                break;
                case 2:
                     if(b=="2")
                {b="X";}
                else
                {System.out.println("Repeated");}
                break;
                case 3:
                     if(c=="3")
                {c="X";}
                else
                {System.out.println("Repeated");}
                break;
                case 4:
                     if(d=="4")
                {d="X";}
                else
                {System.out.println("Repeated");}
                break;
                case 5:
                     if(e=="5")
                {e="X";}
                else
                {System.out.println("Repeated");}
                break;
                case 6:
                     if(f=="6")
                {f="X";}
                else
                {System.out.println("Repeated");}
                    break;
                    case 7:
                         if(g=="7")
                {g="X";}
                else
                {System.out.println("Repeated");}
                        break;
                        case 8:
                             if(h=="8")
                {h="X";}
                else
                {System.out.println("Repeated");}
                            break;
                            case 9:
                                 if(i=="9")
                                {i="X";}
                else
                {System.out.println("Repeated");}
                                break;
                          default:
                              System.out.println("Wrong choice");
                              break;
                            }
                            s="|-----|-----|-----|"+'\n'+"|  "+a+"  |  "+b+"  |  "+c+"  |"+'\n'+"|-----|-----|-----|"+'\n'+"|  "+d+"  |  "+e+"  |  "+f+"  |"+'\n'+"|-----|-----|-----|"+'\n'+"|  "+g+"  |  "+h+"  |  "+i+"  |"+'\n'+"|-----|-----|-----|";
      
                            System.out.println(s);
                            if (((a==b)&&(b==c)&&(a=="X"))||((d==e)&&(e==f)&&(d=="X"))||((g==h)&&(h== i)&&(g=="X"))||((a==e)&&(e==i)&&(i=="X"))||((c==e)&&(e==g)&&(g=="X"))||((a==d)&&(d==g)&&(g=="X"))||((b==e)&&(e==h)&&(h=="X"))||((c==f)&&(f==i)&&(i=="X")))
                            {System.out.println("X wins");
                                break;
                            }
                            else if(((a==b)&&(b==c)&&(a=="O"))||((d==e)&&(e==f)&&(d=="O"))||((g==h)&&(h==i)&&(g=="O"))||((a==e)&&(e==i)&&(i=="O"))||((c==e)&&(e==g)&&(g=="O"))||((a==d)&&(d==g)&&(g=="O"))||((b==e)&&(e==h)&&(h=="O"))||((c==f)&&(f==i)&&(i=="O")))
                            {System.out.println("O wins");
                                break;}
                                else if((a!="1")&&(b!="2")&&(c!="3")&&(d!="4")&&(e!="5")&&(f!="6")&&(g!="7")&&(h!="8")&&(i!="9"))
                                {System.out.println("Draw");
                                break;}
                                
                                else{System.out.println("");
                                }System.out.println("Turn of O");
                                int v=in.nextInt();
                                switch(v)
            {case 1:
                if(a=="1")
                {a="O";}
                else
                {System.out.println("Repeated");}
                break;
                case 2:
                     if(b=="2")
                {b="O";}
                else
                {System.out.println("Repeated");}
                break;
                case 3:
                     if(c=="3")
                {c="O";}
                else
                {System.out.println("Repeated");}
                break;
                case 4:
                     if(d=="4")
                {d="O";}
                else
                {System.out.println("Repeated");}
                break;
                case 5:
                     if(e=="5")
                {e="O";}
                else
                {System.out.println("Repeated");}
                break;
                case 6:
                     if(f=="6")
                {f="O";}
                else
                {System.out.println("Repeated");}
                    break;
                    case 7:
                         if(g=="7")
                {g="O";}
                else
                {System.out.println("Repeated");}
                        break;
                        case 8:
                             if(h=="8")
                {h="O";}
                else
                {System.out.println("Repeated");}
                            break;
                            case 9:
                                 if(i=="9")
                                {i="X";}
                else
                {System.out.println("Repeated");}
                                break;
                          default:
                              System.out.println("Wrong choice");
                              break;
                            }
                            s="|-----|-----|-----|"+'\n'+"|  "+a+"  |  "+b+"  |  "+c+"  |"+'\n'+"|-----|-----|-----|"+'\n'+"|  "+d+"  |  "+e+"  |  "+f+"  |"+'\n'+"|-----|-----|-----|"+'\n'+"|  "+g+"  |  "+h+"  |  "+i+"  |"+'\n'+"|-----|-----|-----|";
      
                            System.out.println(s);
                            if (((a==b)&&(b==c)&&(a=="X"))||((d==e)&&(e==f)&&(d=="X"))||((g==h)&&(h== i)&&(g=="X"))||((a==e)&&(e==i)&&(i=="X"))||((c==e)&&(e==g)&&(g=="X"))||((a==d)&&(d==g)&&(g=="X"))||((b==e)&&(e==h)&&(h=="X"))||((c==f)&&(f==i)&&(i=="X")))
                            {System.out.println("X wins");
                                break;
                            }
                            else if(((a==b)&&(b==c)&&(a=="O"))||((d==e)&&(e==f)&&(d=="O"))||((g==h)&&(h==i)&&(g=="O"))||((a==e)&&(e==i)&&(i=="O"))||((c==e)&&(e==g)&&(g=="O"))||((a==d)&&(d==g)&&(g=="O"))||((b==e)&&(e==h)&&(h=="O"))||((c==f)&&(f==i)&&(i=="O")))
                            {System.out.println("O wins");
                                break;}
                                else if((a!="1")&&(b!="2")&&(c!="3")&&(d!="4")&&(e!="5")&&(f!="6")&&(g!="7")&&(h!="8")&&(i!="9"))
                                {System.out.println("Draw");
                                break;}
                                
                                else{System.out.println("");
                                }}}}
