# define the environnement variable SRC_DIR
LIBS= RAMP Random
      
all: $(LIBS)

% : $(SRC_DIR)/%.F90
	elmerf90  $< -o $@

clean:
	rm -f $(LIBS)
