```swift

import UIKit
 
var answerA = String.init("Brazil")
var answerB = String.init("United States")
var answerC = String.init("Italy")



class GameViewController: UIViewController {

    
    @IBOutlet weak var stageLabel: UILabel!
    
    @IBOutlet weak var imageView: UIImageView!
    
    
    override func viewDidLoad() {
        super.viewDidLoad()
        imageView.image =  UIImage.init(named: "USA")
    }

    
    
    @IBAction func answerAButton(_ sender: Any) {
    }
    
    
    @IBAction func answerBButton(_ sender: Any) {
    }
    
    
    @IBAction func answerCButton(_ sender: Any) {
    }
    
    
}

func correctGuess() {
    
}


func wrongGuess() {
    
}

```



