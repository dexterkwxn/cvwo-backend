# cvwo-backend

# To configure for local set-up, modify the main.go file to include your db config

	cfg := mysql.Config{
		User:   "b128a6f15bb789",
		Passwd: "cc8c3882",
		Net:    "tcp",
		Addr:   "us-cdbr-east-05.cleardb.net",
		DBName: "heroku_94064b77a7dac8a",
	}

# Starting the Backend

navigate to the backend directory, and do

// go mod tidy

then start the backend with 

// go run .
