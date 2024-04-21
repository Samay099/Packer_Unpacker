# Backend

## Packing Backend

### Pack Method
    
    private void Pack()
 
#### Description-

* Creates a new regular file as the name specified by the user.

* Opens the directory and traverses each file from that directory.

* Writes Metadata as header and actual file data in sequence of the files in directory in newly created file

#### Parameters
    None

#### Return Value 
    void

![Pack()](/assets/images/Pack.png)

## Unpacking Backend

### UnPack Method
    
    private void UnPack()
 
#### Description-

* Opend the Packed file in read mode

* Readds the header, from the name specified in header creates new file.

* Writes data into newly created file from packed file.

* Repeats all above steps till the end of file 

#### Parameters
    None

#### Return Value 
    void

![Pack()](/assets/images/UnPack.png)


# Frontend

## Login Frame

### Login Class Constructor

    public Login_Frame()

#### Description-
* Creates a Frame with two labels, a text field, a password field and a button 

* Displays error for incorrect credentials

#### Parameters
    None

![LoginC](/assets/images/LoginConstructor.png)

### Action Performed Method

        public void actionPerformed(ActionEvent aobj) 

#### Description-
* Method of Action Listner interface

* Takes ActionEvent object
as parameter

* Handles the action performed on the login 

* Authencates the Username and Password

#### Parameters
    aobj : ActionEvent object
#### Return Value
    void

![LoginAP](/assets/images/LoginActionPerformed.png)

## Main Frame

### Main Class Constructor

    public Main_Frame()

#### Description-
* Creates a Frame with two buttons Pack and Unpack

#### Parameters
    None

![MainC](/assets/images/MainConstructor.png)

### Action Performed Method

        public void actionPerformed(ActionEvent aobj) 

#### Description-
* Method of Action Listner interface

* Takes ActionEvent object
as parameter

* Handles the action performed on the main frame

#### Parameters
    aobj : ActionEvent object
#### Return Value
    void

![MainAP](/assets/images/MainActionPerformed.png)


## Packer Frame

### Packer Class Constructor

    public Packer_Frame()

#### Description-
* Creates a Frame with two text fields and labels to take input and two buttons

* Submit button initiates the Packer backend

* Previous returns to main frame

#### Parameters
    None

![PackerC](/assets/images/PackerConstructor.png)

### Action Performed Method

        public void actionPerformed(ActionEvent aobj) 

#### Description-
* Method of Action Listner interface

* Takes ActionEvent object
as parameter

* Handles the action performed on the Packer frame

#### Parameters
    aobj : ActionEvent object
#### Return Value
    void

![PackerC](/assets/images/PackerConstructor.png)


## Unpacker Frame

### Unpacker Class Constructor

    public Unpacker_Frame()

#### Description-
* Creates a Frame with a text field, lable to take input and two buttons

* Submit button initiates the Unpacker backend

* Previous returns to main frame

#### Parameters
    None

![UnpackerC](/assets/images/UnpackerConstructor.png)

### Action Performed Method

        public void actionPerformed(ActionEvent aobj) 

#### Description-
* Method of Action Listner interface

* Takes ActionEvent object
as parameter

* Handles the action performed on the Unpacker frame

#### Parameters
    aobj : ActionEvent object
#### Return Value
    void

![UnpackerAP](/assets/images/UnpackerActionPerformer.png)