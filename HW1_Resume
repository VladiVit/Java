public class Main {

    public static class Org {
        public String orgName;
        public String orgAddress;
        public String orgSite;
        public String orgPhone;
    }

    public static class Resume {
        public int experience;      //опыт специалиста
        public int age;             //возраст специалиста
        public String name;         //имя специалиста
        public String address;      //адрес проживания
        public String eMail;        //эдектронный адрес
        public String phoneNumber;  //телефон
        public String education;    //образование
        public Org org = new Org(); //место работы
    }

    public static void main(String[] args) {
        Resume human = new Resume();
        human.name = "Egorov";
        human.age = 20;
        human.address = "Moscow, Lenin street, 23";
        human.phoneNumber = "123-45-67";
        human.education = "higher";
        human.eMail = "EgorovEE@gmail.com";
        human.experience = 2;
        human.org.orgAddress = "Moscow, First street, 3";
        human.org.orgName = "OOO Flash";
        human.org.orgPhone = "333-33-33";
        human.org.orgSite = "www.flash.com";

        System.out.println(human.name);
        System.out.println(human.age);
        System.out.println(human.address);
        System.out.println(human.phoneNumber);
        System.out.println(human.education);
        System.out.println(human.eMail);
        System.out.println(human.experience);
        System.out.println(human.org.orgAddress);
        System.out.println(human.org.orgName);
        System.out.println(human.org.orgPhone);
        System.out.println(human.org.orgSite);
    }
}
