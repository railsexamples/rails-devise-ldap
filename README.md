# rails-devise-ldap-example

    host: ENV["LDAP_HOST"]
    port: ENV["LDAP_PORT"]
    attribute: ENV["LDAP_ATTRIBUTE"] #uid
    base: ENV["LDAP_BASE"] #ou=People,dc=omu,dc=edu,dc=tr
    admin_user: ENV["LDAP_ATTRIBUTE"]=ENV["LDAP_USERNAME"],ENV["LDAP_BASE"]
    admin_password: ENV["LDAP_PASSWORD"]
