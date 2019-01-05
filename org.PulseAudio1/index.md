:kind       | :path                                  | :return      | :root           | :sig                                                                                                  
----------- | -------------------------------------- | ------------ | --------------- | ------------------------------------------------------------------------------------------------------
method      | /org/freedesktop/ReserveDevice1/Audio0 | QDBusVariant | org.PulseAudio1 | org.freedesktop.DBus.Properties.Get(QString interface, QString property)                              
method      | /org/freedesktop/ReserveDevice1/Audio0 | QString      | org.PulseAudio1 | org.freedesktop.DBus.Introspectable.Introspect()                                                      
method      | /org/freedesktop/ReserveDevice1/Audio0 | bool         | org.PulseAudio1 | org.freedesktop.ReserveDevice1.RequestRelease(int priority)                                           
prop (read) | /org/freedesktop/ReserveDevice1/Audio0 | QString      | org.PulseAudio1 | org.freedesktop.ReserveDevice1.ApplicationDeviceName                                                  
prop (read) | /org/freedesktop/ReserveDevice1/Audio0 | QString      | org.PulseAudio1 | org.freedesktop.ReserveDevice1.ApplicationName                                                        
prop (read) | /org/freedesktop/ReserveDevice1/Audio0 | int          | org.PulseAudio1 | org.freedesktop.ReserveDevice1.Priority                                                               
method      | /org/pulseaudio/server_lookup1         | QDBusVariant | org.PulseAudio1 | org.freedesktop.DBus.Properties.Get(QString interface_name, QString property_name)                    
method      | /org/pulseaudio/server_lookup1         | QString      | org.PulseAudio1 | org.freedesktop.DBus.Introspectable.Introspect()                                                      
method      | /org/pulseaudio/server_lookup1         | QVariantMap  | org.PulseAudio1 | org.freedesktop.DBus.Properties.GetAll(QString interface_name)                                        
method      | /org/pulseaudio/server_lookup1         | void         | org.PulseAudio1 | org.freedesktop.DBus.Properties.Set(QString interface_name, QString property_name, QDBusVariant value)
prop (read) | /org/pulseaudio/server_lookup1         | QString      | org.PulseAudio1 | org.PulseAudio.ServerLookup1.Address                                                                  
