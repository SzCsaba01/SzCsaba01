```C#

package SzikszaiCsaba;

class About : Me{

    public string getCurrentStudies(){
        return "3rd year Computer Science student at Technical University of Cluj-Napoca";
    }
    
    public ArrayList getInterests(){
        ArrayList<string> interests = new ArrayList<string>();
        interests.add("Programming");
        interests.add("Meditation");
        interests.add("Reading");
        interests.add("Self-improvement");
        interests.add("Body building");
        interests.add("Outdoor activities");
        
        return interests;
    }
    
    public string getFutureGoal(){
        return "To contribute to open source and learning new technologies";
    }
}
    
    
