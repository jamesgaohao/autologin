# $language = "Python"
# $interface= "1.0"
def parseFile():
          cfg_set=[]
          file_cfg = open("XXX.XXX")
          for line in file_cfg:
                      s = line.split(" ")
                      ip = s[0]
                      username = s[1]
                      user_pwd = s[2]
                      app_name = s[3]
                      app_pwd = s [4]
                      cfg_set.append(s)
           return cfg_set
           
           
           
def main():
cfg_set = parsefile()
 for cfg_tmp in cfg_set:
             login_str = "/SSH /PASSWORD %s %s@%s %(cfg_tmp[2],cfg_tmp[1],cfg_tmp[0])"
             crt.Session.Connect(login_str,Ture)
             
 mian()
