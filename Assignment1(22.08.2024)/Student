package ClassWork;

public class Student {
    private long id;
    private String branch;



    private char gender;
    private String name;
    public String getName() {
        return name;
    }

    public boolean setName(String name) {
       if(name.matches("[a-z A-Z]+")){
           this.name = name;
           return true;
       }
       return false;
    }

    public long getId() {
        return id;
    }


    public boolean setId(long id) {
        if(id>=100000000 && id<=999999999){
            this.id = id;
            return true;
        }
        return false;

    }

    public String getBranch() {
        return branch;
    }

    public boolean setBranch(String branch) {
        if(branch.equalsIgnoreCase("bca") || branch.equalsIgnoreCase("mca") ){
            this.branch = branch;
            return true;

        }
        return false;

    }

    public char getGender() {
     return gender;
    }

    public boolean setGender(char gender) {
        if(gender=='m' || gender=='f' || gender=='M' || gender=='F' ){
            this.gender = gender;
            return true;
        }
        return false;
    }
    @Override
    public String toString() {
        return "Student{" +
                "id=" + id +
                ", branch='" + branch + '\'' +
                ", gender=" + gender +
                ", name='" + name + '\'' +
                '}';
    }

}
