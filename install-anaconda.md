# Install-Anaconda
### linux རུ Anaconda འཛུགས་ཚུལ།
"""
    Anaconda ཡིས་དཀའ་ལས་སྐུ་ཚེགས་མེད་པར Python ཡི་དཔེ་གཟུགས་དག་ནང་འཇུག་བྱེད་ཐུབ།
            ད་དུང་དཔེ་གཟུགས་ཀྱི་རིམ་པར་དོ་དམ་ལེགས་པོའང་བྱེད་ཐུབ།
"""
དང་པོ།  དྲྭ་གནས https://www.anaconda.com/download/ ནས་འཇུག་བྱེད་བྱ་རིམ་ཕབ་ལེན་བྱ་དགོས།
     དེ་ལས་རང་གི་དགོས་མཁོ་ལྟར། རྒྱུད་ཁུངས་གང་དང་རིམ་པ་གང་དགོས་སོགས་རང་དགར་གདམ་ཆོག
     སྐབས་འདིར་ཕབ་ལེན་བྱས་པའི་བྱ་རིམ་ནི Anaconda3-5.0.1-Linux-x86_64.sh ཡིན།
     དེའི་རིམ་པ་ནི  3-5.0.1 ཡིན།
     
གཉིས་པ། གོང་དུ་ཕབ་ལེན་བྱས་ཟིན་པའི་བྱ་རིམ་གྱི་ཕབ་གནས་ནས་བཀོལ་སྣེ་ཡི་ཁ་ཕྱེས་ཏེ། 
        བཀའ་ཡིག bash Anaconda3-5.0.1-Linux-x86_64.sh ལག་བསྟར་བྱ་དགོས།
        ༼༡༽  Please, press ENTER to continue >>>
             འཆར་ཚེ།  ཕྱིར་རྫོགས་མཐེམ་གཞུང་མནན་དགོས། (Enter key)
        ༼༢༽ Do you accept the license terms? [yes|no] >>>
            འཆར་ཚེ།     yesགདམ་དགོས།
        ༼༣༽ Anaconda3 will now be installed into this location:
            /yourpath/anaconda3
                - Press ENTER to confirm the location
                - Press CTRL-C to abort the installation
                - Or specify a different location below

            [/yourpath/anaconda3] >>> 
             འཆར་ཚེ།  bash ཡིན་ན་ཕྱིར་རྫོགས་མཐེབ་གཞུང་མནན་པས་ཆོག་གོ
             zsh ཡིན་ན་བཀའ་ཡིག echo 'export PATH="~/anaconda3/bin:$PATH"' >> ~/.zshrc 
             ལག་བསྟར་བྱ་དགོས། 
གསུམ་པ། ནང་འཇུག་ཐུབ་མིན་ལ་ཞིབ་བཤེར་བྱེད་པ། 
    བཀོལ་སྣེ་རུ་བཀའ་ཡིག which conda ཡང་ན conda --version སོགས་བཀོལ་རུང་ན་ལེགས་གྲུབ་བྱུང་བའི་རྟགས། དེ་མིན་ན་ལེགས་གྲུབ་བྱུང་མེད་དོ། 
བཞི་བ། conda ཡིས་དཔེ་གཟུགས་ནང་འཇུག་བྱེད་ཚུལ། 
    ནང་འཇུག་བྱེད་ཚུལ་ནི pip དང ཧ་ཅང་འདྲ་སྟེ། conda install numpy བྱས་པས་ཆོག


Anaconda ཡི་རིམ་པ་འཕར་འདོད་ན། 
    བཀའ་ཡིག 
        conda update conda
        conda updata anaconda  ཡིས་ཆོག
        
Anaconda སུབ་འདོད་ན།
    དེ་ནི་ཧ་ཅང་སླ་སྟེ། བཀའ་ཡིག rm -rf anaconda ལག་བསྟར་བྱེད་དེ། ད་དུང་ ~/.bashrc ཡང་ན ~/.zshrc ཁྲོད་ཀྱི་དེའི་འབྲེལ་གནས
    'export PATH="~/anaconda3/bin:$PATH"' བསུབ་དགོས། 
