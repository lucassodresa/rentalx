# Register a car

**RF**
- It should be possible to register a new car.
- It should be possible to list all categories.

**RN**
- It should not be possible to register a car with an existing license plate.
- It should not be possible to edit the license plate of an existing car.
- The car should be registered as available by default.
- The user role responsible for registration should be an administrator.



# List cars

**RF**
- It should be possible to list all available cars.
- It should be possible to list all available cars by name of the category.
- It should be possible to list all available cars by name of the brand.
- It should be possible to list all available cars by name of the car.

**RN**
- The user doesn't need to be authenticated.


# Register specification in car

**RF**
- It should be possible to register a specification for the car.
- It should be possible to list all specifications.
- It should be possible to list all cars.

**RN**
- It should not be possible to register a specification to a non-registered car.
- It should not be possible to register a specification that already exists in a car.
- The user role responsible for registration should be an administrator.


# Register car image

**RF**
- It should be possible to register a car image.
- It should be possible to list all cars.

**RNF**
- Use multer to file upload.

**RN**
- The user should be able to register multiple images to the same car.
- - The user role responsible for registration should be an administrator.

# Car rent

**RF**
- It should be possible to register a rent.

**RN**
- The rent should have a minimum duration of 24 hours.
- It should not be possible to register a new rent if already exists some opened rent to the same user.
- It should not be possible to register a new rent if already exists some open rent for the same car.