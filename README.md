# SessionWrapper

        // configurations
      define('SESSION_NAME', "session_name_here");                      // Set session name : string
      define('SESSION_MAX_LIFE_TIME', 0);
      define('SESSION_PATH', '/');
      define('SESSIONS_DIR', 'your-folder-path-here');      // The path of sessions dir
      define('SESSIONS_DOMAIN', 'sub_domain');            // Your sub domain  ex: (.test.com)
      define('SESSIONS_CIPHER_METHOD', 'aes-128-ctr');
      
      
      
## Guide to use

        $sessionObj = new SessionWrapper();
        
        // start the session
        $sessionObj->start();

        //set value
        $sessionObj->VariableName = Value;
        
        // examples
        $sessionObj->username = "mustafa";
        $sessionObj->address  = "Giza";
        
        //get value
        $sessionObj->VariableName;
        
        // examples
        echo $sessionObj->username;
        echo $sessionObj->address;

        // stop session
        $sessionObj->sessionDestroy();

        
            
            
            
            
            




