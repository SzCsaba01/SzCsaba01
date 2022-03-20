```java

package SzikszaiCsaba;

class About extends Me{

    public String getCurrentStudies(){
        return "2nd year Computer Science student at Technical University of Cluj-Napoca";
    }
    
    public ArrayList getInterests(){
        ArrayList<String> interests = new ArrayList<String>();
        interests.add("Programming");
        interests.add("Meditation");
        interests.add("Reading");
        interests.add("Self-improvement");
        interests.add("Body building");
        interests.add("Outdoor activities");
        
        return interests;
    }
    
    public String getFutureGoal(){
        return "To contribute to open source and learning new technologies";
    }
}
    
    
