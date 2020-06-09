# Lika Kharatishvili

* **(+995) 599-34-51-46** 
* [lika.kharatishvili.1@btu.edu.ge](lika.kharatishvili.1@btu.edu.ge) 
* Telegram Username - @Likaxara
* Skype - live:.cid.5b4f87fbbd8ee139
* **Tbilisi, Georgia**  

## Summary:

For me, front-end development is a critical component of what I’m passionate about, so I take it seriously. It enabled me to easily put my ideas into digital form and get results back really quick.
Mostly I'm self taugh, trying really hard to become an awesome front-end developer. I take a lot of Udemy and Pluralsight courses.
**I always going to do my best, no matter where I am.**


## Skills
◾◾◾◾◽ HTML5  
◾◾◾◾◽ CSS3  
◾◾◾◽◽ SCSS  
◾◾◾◽◽ Javascript    
◾◾◾◽◽ Angular  
◾◾◽◽◽ GIT   
◾◾◾◾◽ Photoshop  
◾◾◽◽◽ Adobe XD  

### Code Examples

``` Angular
 user: User;
  constructor(
    private route: ActivatedRoute,
    private usersService: UsersService,
    private location: Location
  ) {}

  ngOnInit() {
    this.getDetails();
  }
  
  getDetails() {
    this.route.params.subscribe((params: Params) => {
      const userName = params['username'];
      this.usersService.getUser(userName).subscribe((responsedUser: User) => {
      this.user = responsedUser;
    });
    });
  }

  goBack(): void {
    this.location.back();
  }
```
``` SCSS
 .el:hover, .el.active {
    color: #fff;
    background-color: #000000;
    border-color: transparent;
    svg {
      fill: #fff;
    }
  }
  .el.disabled:hover {
    cursor: default;
    background-color: #fbfbfb;
    border-color: #cccccc;
    svg {
      fill: #a7a7a7;
    }
  }

```

## Education

**General Education Diploma**
* Buckswood International School  
_2004 - 2016_

**Computer Science**
* Simon Fraser University   
_2016 - 2018_

**Computer Science**
* Business and Technology University    
_2019 - Present_

## Experience

**Project Manager Assistant** 
* T-estate Georgia  
_2018_

### English:
* I have an IELTS Certificate ( LEVEL B2 )




