# Compiler
CXX = g++

# Directories
SRC_DIR = src
INC_DIR = include
BIN_DIR = bin

# Files
SRC_FILES = $(SRC_DIR)/hello_window_clear.cpp $(SRC_DIR)/glad.c
OUT_FILE = $(BIN_DIR)/app

# Flags
CXXFLAGS = -I$(INC_DIR)
LDFLAGS = -lglfw -ldl -lGL

# Default target
all: $(OUT_FILE)

# Build rule
$(OUT_FILE): $(SRC_FILES)
	@mkdir -p $(BIN_DIR)
	$(CXX) $(SRC_FILES) -o $(OUT_FILE) $(CXXFLAGS) $(LDFLAGS)

# Clean build artifacts
clean:
	rm -rf $(BIN_DIR)

# Run the app
run: all
	./$(OUT_FILE)

.PHONY: all clean run
