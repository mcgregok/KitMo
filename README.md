# KitMo — Free UI Images for iPhone Developers

After getting tired of tracking down decent UI button images that had retina deplay support I made my own.  Here they are.

##USAGE:

Add the .png and the @2x.png you want to your project

    
    - (void)viewDidLoad 
    {
        /*Your app code here*/
     
        UIImage *buttonImageNormal = [UIImage imageNamed:@"KitMoRedUIButton.png"];
    
        UIImage *stretchableButtonImageNormal = [buttonImageNormal stretchableImageWithLeftCapWidth:12 topCapHeight:0]; 
    
        [myUIButton setBackgroundImage:stretchableButtonImageNormal forState:UIControlStateNormal];
        [myUIButton setTitleColor:[UIColor colorWithWhite:1.0f alpha:1.0f] forState:UIControlStateNormal];
    																			     
        [super viewDidLoad];
    }
    

...