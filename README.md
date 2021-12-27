# java-example



    public static boolean contieneSoloLetras(String cadena) {
            for (int x = 0; x < cadena.length(); x++) {
                char c = cadena.charAt(x);
                // Si no está entre a y z, ni entre A y Z, ni es un espacio
                if (!((c >= 'a' && c <= 'z') || (c >= 'A' && c <= 'Z') || c == ' ')) {
                    return false;
            }
        }
    return true;
    
    String str = "Character";
        System.out.println(str.contains("h"));
        System.out.println(str.contains("Char"));
        System.out.println(str.contains("ac"));
        System.out.println(str.contains("v"));
        System.out.println(str.contains("vl")); 
        
        String s1 = "This is String CharAt Method";
        //returns the char value at the 0 index
        System.out.println("Character at 0 position is: " + s1.charAt(0));
        //returns the char value at the 5th index
        System.out.println("Character at 5th position is: " + s1.charAt(5));
        //returns the char value at the 22nd index
        System.out.println("Character at 22nd position is: " + s1.charAt(22));
        //returns the char value at the 23th index
        char result = s1.charAt(-1);
        System.out.println("Character at 23th position is: " + result);


  System.out.println("is not blak "+StringUtils.isNotBlank(cadena));
    	System.out.println("is black sin espacio "+StringUtils.isBlank(cadena));
    	System.out.println("is black con espacio"+StringUtils.isBlank(cadena3));
    	System.out.println("is not empity "+StringUtils.isEmpty(cadena2));
    	System.out.println("eliminsdo espacios "+cad);
    	System.out.println("is numeric "+StringUtils.isNumeric(numero2));
    	boolean e="aB".matches("[a-zA-Z]*");
    	if (nuevo.charAt(0)=='c' || nuevo.charAt(0)=='C' ) {
    		System.out.println("tiene un ");
    		
            StringBuffer sbf = new StringBuffer("raghav");
            System.out.println("String buffer before deletion = " + sbf);
      
            // Deleting the character at indexpoint 5
            sbf.deleteCharAt(5);
            System.out.println("After deletion new StringBuffer = " + sbf);
    		
    		
    		StringBuilder a = new StringBuilder();
    		a.append(nuevo);
    		a.deleteCharAt(0);
    		System.out.println("la nueva cadena es "+a);
    	}
    	System.out.println("con match "+ nuevo.charAt(0));
		return cadena;
