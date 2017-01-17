static int[][] polja = new int[50][50];
    static int smer = 3;
    static int glava_x = 25;
    static int glava_y = 25;
    static int rep_x =25;
    static int rep_y= 25;
    static int [] smeri = new int[2500];
    static int dolzina = 1;
    public static void glavna(){
        
        if(smer==3){
            glava_y--;
        }
        if(smer==1){
            glava_y++;
        }
        if(smer==0){
            glava_x++;
        }
        if(smer==2){
            glava_x--;
        }
        
        polja[glava_x][glava_y] = 1;
        polja[rep_x][rep_y]=0;
        
        
        
    
    }
