# Display Fullname Service

## Instructions

1. **Create the project folder**:
   - Create a folder named `display-fullname-service`.

2. **Create the Ruby file**:
   - Inside the `display-fullname-service` folder, create a file named `display_fullname.rb`.
   - Paste the following Ruby code snippet into the `display_fullname.rb` file:

   ```ruby
   # Uncomment this if you already created the service file
   # require_relative "display_fullname_service"
    
   # Usage: ruby display_fullname.rb John Doe

   firstname = ARGV[0]
   lastname  = ARGV[1]

   puts "Hello, #{firstname} #{lastname}"

   # Your Task: Create a service class that will initialize firstname and lastname and will print the fullname by invoking the call method

   # Uncomment this if you have already completed the service class
   # display_fullname_service = DisplayFullnameService.new(firstname, lastname)
   # puts display_fullname_service.call

   # Final Output:
   # Hello, John Doe
   # Hello, John Doe

3. **Follow the instructions in the code**:
   - Complete the tasks outlined in the code snippet, including creating the `DisplayFullnameService` class and testing the output.
