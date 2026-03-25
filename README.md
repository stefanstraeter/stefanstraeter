<h1 align="center">
  Hi there, I'm Stefan!
</h1>

<p align="center">
  <a href="https://github.com/stefanstraeter">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00FF99&center=true&vCenter=true&width=500&lines=On+the+path+to+Full-Stack+Excellence;From+curiosity+to+creation;Passionate+about+Web+Development" alt="Typing SVG" />
  </a>
</p>

```typescript
/**
 * @description Transitioning from curiosity to full-stack creation.
 * Focused on scalable web architecture and clean UI/UX.
 */
export class StefanStraeter implements IDeveloper, IContinuousLearner {
    
    // CORE IDENTITY
    public readonly fullName: string = "Stefan Sträter";
    public readonly role: string     = "Full-Stack Software Developer (In Training)";
    public readonly location: string = "Innsbruck, Austria";

    // TECH STACK
    public frontend: string[] = ["JavaScript (ES6+)", "HTML5", "CSS3", "Bootstrap", "Angular (Learning)"];
    public backend: string[]  = ["Firebase API", "Node.js (Learning)"];
    public design: string[]   = ["Figma", "Photoshop"];

    // MINDSET
    public traits: string[] = ["Curious", "Creative", "Problem Solver", "Team Player"];

    /**
     * @returns The current mission objective.
     */
    public getCurrentFocus(): string {
        return "Mastering the gap between Frontend and Backend to build seamless digital products.";
    }

    // LET'S CONNECT
    public connect(): void {
        const github: string   = "[https://github.com/stefanstraeter](https://github.com/stefanstraeter)";
        const linkedIn: string = "[https://www.linkedin.com/in/stefan-straeter](https://www.linkedin.com/in/stefan-straeter)";
        
        window.open(github, '_blank');
        window.open(linkedIn, '_blank');
    }
}


