# Summer-camp-ros2-session

Clone repository : `https://github.com/rignitc/summer-camp-ros2-session.git`

Build the workspace : `colcon build`

Source workspace : `source install/setup.bash`

### Run talker listener example

Run publisher : `ros2 run simple_publisher_subscriber talker` 

Run subscriber : `ros2 run simple_publisher_subscriber listener`

### Run service client example

Run service : `ros2 run simple_service_client service `

Run cllient : `ros2 run simple_service_client client 6 8`

### Run action server example 

Run action service : `python3 fibonacci_action_server.py`

Run action client : `python3 fibonacci_action_client.py`

