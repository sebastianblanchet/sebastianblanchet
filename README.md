void copyinfo(w) {
  size_t len;
  char *buf; 
  
  len = read_int_from_network();
  buf = malloc(len+10);
  read(info, buf, len);
  
  }
