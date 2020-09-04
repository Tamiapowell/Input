    public static void main(String[] args) {
	// write your code here
        Scanner eliza = new Scanner(System.in);
        System.out.println(" Welcome to Eliza chats! My name is Eliza, What is your name?");
        String name = eliza.nextLine();
        System.out.println( "Hi, " + name + " How are you doing today?" );
        String feelings = eliza.nextLine();
        System.out.println("Well " + name + "what has you feeling " + feelings + "?, did anything in particular happen today? ");
        String moreInfo = eliza.nextLine();
        System.out.println("I understand! so today you " + moreInfo + "lets start by examining how " + moreInfo+ "impacted \n " +
                " how you feel today, and how the choices you've made after impacted how you feel");
        String more = eliza.nextLine();
        System.out.println( name + ", Name a choice you made today that could've impacted how you feel ?");
        String choice = eliza.nextLine();
        System.out.println("Think about that choice and we will discuss more next time. Have a nice day!");
        String responses = "Here are your responses: ";

        System.out.println(responses +  name+", " +  feelings+", " + moreInfo+", "+ more+", "+choice);



    }
}
