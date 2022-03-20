```java

package SzikszaiCsaba;

class About extends Me{

    public String getCurrentStudies(){
        return "Computer Science Technical University of Cluj-Napoca";
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
        return "To contribute to open source, learning new technologies";
    }
}
    
    
