# squirrelPlay
public boolean squirrelPlay(int temp, boolean isSummer) {
  if (!isSummer && temp >= 60 && temp <= 90){
    return true;
  }
  else if (isSummer == true && temp >= 60 && temp <= 100){
    return true;
  }
  return false;
}
