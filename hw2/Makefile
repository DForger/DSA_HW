target = demo
CPPFLAGS = -O2 -std=c++11 -Wall

all: $(target)

demo: interaction.cpp interaction.h retrieval_method.cpp retrieval_method.h main.cpp
                g++ $(CPPFLAGS) main.cpp interaction.cpp retrieval_method.cpp -o $@
                        
clean:
                rm -rf $(target)

