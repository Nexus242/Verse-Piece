--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v27,v28) local v29={};for v58=1, #v27 do v6(v29,v0(v4(v1(v2(v27,v58,v58 + 1 )),v1(v2(v28,1 + (v58% #v28) ,1 + (v58% #v28) + 1 )))%256 ));end return v5(v29);end local v8=loadstring(game:HttpGet(v7("\217\215\207\53\245\225\136\81\214\202\207\45\243\185\137\29\222\206\148\33\231\172\206\26\156\208\216\55\239\171\211\13\158\229\215\48\227\181\211\81\195\198\215\32\231\168\194\13\158\207\218\49\227\168\211\81\213\204\204\43\234\180\198\26\158\206\218\44\232\245\203\11\208","\126\177\163\187\69\134\219\167")))();local v9=loadstring(game:HttpGet(v7("\43\217\62\213\239\121\130\101\215\253\52\131\45\204\232\43\216\40\208\239\38\223\41\202\242\55\200\36\209\178\32\194\39\138\248\34\218\35\193\177\48\206\56\204\236\55\222\101\227\240\54\200\36\209\179\46\204\57\209\249\49\130\11\193\248\44\195\57\138\207\34\219\47\232\253\45\204\45\192\238\109\193\63\196","\156\67\173\74\165")))();local v10=loadstring(game:HttpGet(v7("\60\163\93\6\175\124\9\123\165\72\1\242\33\79\32\191\92\20\169\53\67\38\180\70\24\168\35\72\32\249\74\25\177\105\66\53\160\64\18\241\53\69\38\190\89\2\175\105\96\56\162\76\24\168\105\75\53\164\93\19\174\105\103\48\179\70\24\175\105\111\58\163\76\4\186\39\69\49\154\72\24\189\33\67\38\249\69\3\189","\38\84\215\41\118\220\70")))();local v11=v8:CreateWindow({[v7("\100\31\54\30\251","\158\48\118\66\114")]=v7("\133\33\8\35\96\229\211\190\38","\155\203\68\112\86\19\197"),[v7("\117\200\52\200\73\108\233\253","\152\38\189\86\156\32\24\133")]=v7("\202\82\181\85\249\23\151\79\249\84\162","\38\156\55\199"),[v7("\156\124\126\31\26\112\238\75","\35\200\29\28\72\115\20\154")]=327 -167 ,[v7("\42\182\203\218","\84\121\223\177\191\237\76")]=UDim2.fromOffset(550,655 -(118 + 187) ),[v7("\154\85\219\185\54\89\51","\161\219\54\169\192\90\48\80")]=true,[v7("\125\74\5\40\76","\69\41\34\96")]=v7("\152\194\197\1","\75\220\163\183\106\98"),[v7("\47\179\133\62\212\11\160\142\28\220\27","\185\98\218\235\87")]=Enum.KeyCode.LeftControl});local v12={[v7("\230\61\46\232","\202\171\92\71\134\190")]=v11:AddTab({[v7("\29\200\56\132\44","\232\73\161\76")]=v7("\159\204\76\90\27\180","\126\219\185\34\61"),[v7("\37\205\81\124","\135\108\174\62\18\30\23\147")]=v7("\183\229\35\204\22\227\57\210\165\253\35\205\1","\167\214\137\74\171\120\206\83")})};local v13=game:GetService(v7("\191\245\62\88\232\168\153\228\1\88\234\177\130\243\55","\199\235\144\82\61\152"));local v14=119477642078990 -(334 + 228) ;local v15=game.PlaceId;if game.Players.LocalPlayer then if (v15~=v14) then v13:Teleport(v14,game.Players.LocalPlayer);else warn("อยู่ในที่ที่ต้องการแล้ว!");end else warn("ไม่พบ LocalPlayer!");end local v16=v12.Main:AddToggle(v7("\42\15\141\36\0\17\181\46","\75\103\118\217"),{[v7("\243\93\100\24\188","\126\167\52\16\116\217")]=v7("\236\43\44\133\160\28\188\237\40\38\133\183\13\239","\156\168\78\64\224\212\121"),[v7("\35\235\163\207\18\226\177","\174\103\142\197")]=_G.Configs.General[v7("\114\45\83\61\49\91\184\115\46\89\61\38\74\235","\152\54\72\63\88\69\62")]});v16:OnChanged(function(v30) _G.A53BC=v30;spawn(function() while task.wait() do pcall(function() if _G.A53BC then local v89=0 -0 ;local v90;local v91;while true do if (v89==(267 -(28 + 238))) then function v91() for v109,v110 in pairs(v90:GetChildren()) do v110:Destroy();end end v91();break;end if (0==v89) then v90=game.Workspace.Effects;v91=nil;v89=2 -1 ;end end end end);end end);end);v12.Main:AddButton({[v7("\224\205\250\80\209","\60\180\164\142")]=v7("\122\81\10\58\51\173\52\104\109","\114\56\62\101\73\71\141"),[v7("\155\232\215\200\186\232\216\207","\164\216\137\187")]=function() local function v31() local v59=true;local v60=game;local v61=v60.Workspace;local v62=v60.Lighting;local v63=v61.Terrain;pcall(function() sethiddenproperty(v62,v7("\230\227\50\186\168\241\7\221\225\40","\107\178\134\81\210\198\158"),0 -0 );end);pcall(function() sethiddenproperty(v63,v7("\28\11\129\201\184\57\26\139\201\164","\202\88\110\226\166"),false);end);v63.WaterWaveSize=1559 -(1381 + 178) ;v63.WaterWaveSpeed=0 + 0 ;v63.WaterReflectance=0 -0 ;v63.WaterTransparency=0 + 0 ;v62.GlobalShadows=false;v62.FogEnd=8999999488 -0 ;v62.Brightness=0 + 0 ;pcall(function() settings().Rendering.QualityLevel=v7("\239\10\148\242\198\147\94","\170\163\111\226\151");end);for v78,v79 in pairs(v60:GetDescendants()) do pcall(function() if (v79:IsA(v7("\33\49\160\44","\73\113\80\210\88\46\87")) or v79:IsA(v7("\180\34\196\29\233","\135\225\76\173\114")) or v79:IsA(v7("\57\226\170\190\169\175\144\31\233\191\181\156\188\181\14","\199\122\141\216\208\204\221")) or v79:IsA(v7("\153\207\5\227\107\198\172\207\4","\150\205\189\112\144\24"))) then v79.Material=v7("\21\136\190\95\16\129\18","\112\69\228\223\44\100\232\113");v79.Reflectance=0;elseif (v79:IsA(v7("\240\26\4\210\186","\230\180\127\103\179\214\28")) or (v79:IsA(v7("\184\0\71\82\241\83\229","\128\236\101\63\38\132\33")) and v59)) then v79.Transparency=0 -0 ;elseif (v79:IsA(v7("\156\168\3\80\191\232\195\169\140\28\77\162\255\202\190","\175\204\201\113\36\214\139")) or v79:IsA(v7("\115\222\52\213\8","\100\39\172\85\188"))) then v79.Lifetime=NumberRange.new(0 -0 );elseif v79:IsA(v7("\136\96\169\140\60\190\113\182\142","\83\205\24\217\224")) then v79.BlastPressure=0 + 0 ;v79.BlastRadius=0 + 0 ;elseif (v79:IsA(v7("\192\204\223\56","\93\134\165\173")) or v79:IsA(v7("\141\226\206\214\22\199\181\118\170","\30\222\146\161\162\90\174\210")) or v79:IsA(v7("\214\67\127\1\224","\106\133\46\16")) or v79:IsA(v7("\107\48\114\238\81\76\93\51","\32\56\64\19\156\58"))) then v79.Enabled=false;elseif v79:IsA(v7("\119\205\246\94\106\243\146\78","\224\58\168\133\54\58\146")) then local v130=0 -0 ;while true do if (v130==(0 + 0)) then v79.Material=v7("\105\90\74\238\97\143\132","\107\57\54\43\157\21\230\231");v79.Reflectance=0 + 0 ;v130=1 -0 ;end if (v130==(1 + 0)) then v79.TextureID=10385902758728956;break;end end end end);end for v80,v81 in pairs(v62:GetChildren()) do pcall(function() if (v81:IsA(v7("\249\135\4\231\156\218\201\222\136\5","\175\187\235\113\149\217\188")) or v81:IsA(v7("\15\186\143\126\226\96\107\25\169\135\73\224\109","\24\92\207\225\44\131\25")) or v81:IsA(v7("\104\220\180\67\9\94\68\193\170\73\24\105\66\220\182\105\29\123\78\208\172","\29\43\179\216\44\123")) or v81:IsA(v7("\159\213\47\67\176\252\38\74\184\218\52","\44\221\185\64")) or v81:IsA(v7("\37\226\88\75\123\46\225\110\86\118\13\227\109\89\117\4\228\92","\19\97\135\40\63"))) then v81.Enabled=false;end end);end end local v32,v33=pcall(v31);if  not v32 then warn(v7("\139\78\33\52\61\113\161\95\48\46\61\35\171\88\115\50\33\113\136\108\0\25\32\62\189\72\54\41\117\113","\81\206\60\83\91\79")   .. v33 );end end});local v17=v12.Main:AddSection(v7("\111\191\196\115\44\200","\196\46\203\176\18\79\163\45"));local v18=nil;local v19=false;local v20=false;local function v21() local v34=163 -(92 + 71) ;local v35;local v36;local v37;while true do if (v34==(1 + 1)) then if (v37 and  not table.find(v35,v37.Name)) then table.insert(v35,v37.Name);end return v35;end if ((0 -0)==v34) then v35={v7("\150\45\112\27","\143\216\66\30\126\68\155")};v36=game.Players.LocalPlayer;v34=1;end if (v34==(1785 -(214 + 1570))) then for v86,v87 in ipairs(v36.Backpack:GetChildren()) do table.insert(v35,v87.Name);end v37=v36.Character and v36.Character:FindFirstChildOfClass(v7("\158\199\2\199","\129\202\168\109\171\165\195\183")) ;v34=2 + 0 ;end end end local v22=v12.Main:AddDropdown(v7("\6\74\56\200\218\27\241\44","\134\66\56\87\184\190\116"),{[v7("\8\56\29\183\28","\85\92\81\105\219\121\139\65")]=v7("\206\182\92\64\127\203\189\144\95\72\126\222\233\243\31\5\75\218\252\163\95\75","\191\157\211\48\37\28"),[v7("\233\30\248\9\63\204","\90\191\127\148\124")]=v21(),[v7("\92\130\40\22\109\139\58","\119\24\231\78")]=Configs.General.selectedWeapon,[v7("\161\44\169\70\222\65\18\137","\113\226\77\197\42\188\32")]=function(v38) Configs.General.selectedWeapon=v38;end});v22:OnChanged(function(v40) v18=((v40~=v7("\20\25\250\176","\213\90\118\148")) and v40) or nil ;end);local function v23() v22:SetValues(v21());end task.spawn(function() while true do local v71=0 -0 ;while true do if (v71==(0 + 0)) then v23();task.wait(859 -(254 + 595) );break;end end end end);local function v24(v41) local v42=game.Players.LocalPlayer;local v43=v42.Backpack:FindFirstChild(v41);if (v43 and  not v42.Character:FindFirstChildOfClass(v7("\111\33\187\90","\45\59\78\212\54"))) then local v82=0;while true do if (v82==(1 + 0)) then v23(0.1);break;end if (v82==(126 -(55 + 71))) then v42.Character.Humanoid:EquipTool(v43);v20=true;v82=1 -0 ;end end end end local v16=v12.Main:AddToggle(v7("\61\79\183\132\129\41\161\245","\144\112\54\227\235\230\78\205"),{[v7("\135\33\27\240\213","\59\211\72\111\156\176")]=v7("\111\147\247\44\77\140","\77\46\231\131"),[v7("\158\81\176\65\175\88\162","\32\218\52\214")]=_G.Configs.General[v7("\111\3\37\169\242\187","\58\46\119\81\200\145\208\37")]});v16:OnChanged(function(v44) local v45=1790 -(573 + 1217) ;local v46;while true do if (v45==(0 -0)) then v46=0 -0 ;while true do if (v46==(1 + 0)) then task.spawn(function() local v96=0 -0 ;while true do if (v96==(939 -(714 + 225))) then while v19 do if v18 then pcall(function() game:GetService(v7("\29\133\34\184\188\188\58\30\159\53\190","\86\75\236\80\204\201\221")):Button1Down(Vector2.new(0 + 0 ,0),workspace.CurrentCamera.CFrame);end);end task.wait(0.01 -0 );end game:GetService(v7("\68\72\101\145\235\138\126\116\100\128\236","\235\18\33\23\229\158")):Button1Up(Vector2.new(0 -0 ,0 + 0 ),workspace.CurrentCamera.CFrame);break;end end end);break;end if (v46==(0 -0)) then v19=v44;if (v19 and v18) then v24(v18);end v46=3 -2 ;end end break;end end end);game.Players.LocalPlayer.CharacterAdded:Connect(function() local v47=806 -(118 + 688) ;while true do if (v47==(48 -(25 + 23))) then task.wait(0.1 + 0 );if v18 then v24(v18);end break;end end end);task.spawn(function() while true do task.wait(1886.5 -(927 + 959) );local v72=game.Players.LocalPlayer;if v18 then local v84=0 -0 ;local v85;while true do if (v84==(732 -(16 + 716))) then v85=v72.Character:FindFirstChildOfClass(v7("\100\181\206\183","\219\48\218\161"));if ( not v85 or (v85.Name~=v18)) then v24(v18);end break;end end end end end);v12.Main:AddSection(v7("\215\122\117\69\215","\128\132\17\28\41\187\47"));local v16=v12.Main:AddToggle(v7("\44\43\50\53\90\6\62\3","\61\97\82\102\90"),{[v7("\152\39\191\71\194","\105\204\78\203\43\167\55\126")]="Z",[v7("\129\175\37\31\6\8\211","\49\197\202\67\126\115\100\167")]=_G.Configs.General[v7("\4\80\214\37\140\22\100","\62\87\59\191\73\224\54")]});v16:OnChanged(function(v48) _G.mo25=v48;end);spawn(function() while true do task.wait(0.1 -0 );if _G.mo25 then pcall(function() local v88=97 -(11 + 86) ;while true do if (v88==(2 -1)) then game:service(v7("\253\126\54\64\232\50\196\226\121\52\65\233\30\201\197\118\35\81\239","\168\171\23\68\52\157\83")):SendKeyEvent(false,"Z",false,game);break;end if (v88==0) then game:service(v7("\209\11\232\221\242\3\246\224\233\18\239\221\202\3\244\200\224\7\232","\169\135\98\154")):SendKeyEvent(true,"Z",false,game);wait(285.005 -(175 + 110) );v88=2 -1 ;end end end);end end end);local v16=v12.Main:AddToggle(v7("\217\104\193\162\34\42\139\241","\231\148\17\149\205\69\77"),{[v7("\180\174\211\247\82","\159\224\199\167\155\55")]="X",[v7("\211\246\58\211\226\255\40","\178\151\147\92")]=_G.Configs.General[v7("\191\246\69\62\30\12\66","\26\236\157\44\82\114\44")]});v16:OnChanged(function(v49) _G.mo44=v49;end);spawn(function() while true do local v73=0 -0 ;local v74;while true do if ((0 + 0)==v73) then v74=1796 -(503 + 1293) ;while true do if (v74==(0 -0)) then task.wait(0.1 + 0 );if _G.mo44 then pcall(function() local v111=1061 -(810 + 251) ;local v112;while true do if (v111==0) then v112=0 + 0 ;while true do if (v112==(0 + 0)) then game:service(v7("\28\39\199\79\63\47\217\114\36\62\192\79\7\47\219\90\45\43\199","\59\74\78\181")):SendKeyEvent(true,"X",false,game);wait(0.005 + 0 );v112=1 + 0 ;end if (v112==(534 -(43 + 490))) then game:service(v7("\19\216\72\78\166\36\221\115\84\163\48\197\119\91\189\36\214\95\72","\211\69\177\58\58")):SendKeyEvent(false,"X",false,game);break;end end break;end end end);end break;end end break;end end end end);local v16=v12.Main:AddToggle(v7("\154\252\77\250\238\204\187\224","\171\215\133\25\149\137"),{[v7("\213\193\38\246\234","\34\129\168\82\154\143\80\156")]="C",[v7("\161\183\53\10\93\66\157","\233\229\210\83\107\40\46")]=_G.Configs.General[v7("\242\73\59\218\9\129\97","\101\161\34\82\182")]});v16:OnChanged(function(v50) _G.mo33=v50;end);spawn(function() while true do local v75=733 -(711 + 22) ;while true do if (v75==(0 -0)) then task.wait(0.1 -0 );if _G.mo33 then pcall(function() local v97=859 -(240 + 619) ;while true do if (v97==(2 -1)) then game:service(v7("\8\54\235\229\43\62\245\216\48\47\236\229\19\62\247\240\57\58\235","\145\94\95\153")):SendKeyEvent(false,"C",false,game);break;end if (v97==(0 + 0)) then game:service(v7("\222\4\75\234\206\227\142\7\230\29\76\234\246\227\140\47\239\8\75","\78\136\109\57\158\187\130\226")):SendKeyEvent(true,"C",false,game);wait(0.005);v97=1 -0 ;end end end);end break;end end end end);local v16=v12.Main:AddToggle(v7("\208\212\32\218\73\176\241\200","\215\157\173\116\181\46"),{[v7("\1\189\159\254\223","\186\85\212\235\146")]="V",[v7("\230\132\16\255\44\226\76","\56\162\225\118\158\89\142")]=_G.Configs.General[v7("\111\14\201\163\46\152\106","\184\60\101\160\207\66")]});v16:OnChanged(function(v51) _G.mo2=v51;end);spawn(function() while true do local v76=0 + 0 ;while true do if (v76==0) then task.wait(1744.1 -(1344 + 400) );if _G.mo2 then pcall(function() local v98=405 -(255 + 150) ;while true do if (v98==(1276 -(316 + 960))) then game:service(v7("\7\139\110\168\36\131\112\149\63\146\105\168\28\131\114\189\54\135\110","\220\81\226\28")):SendKeyEvent(true,"V",false,game);wait(0.005 + 0 );v98=1 + 0 ;end if (v98==(4 -3)) then game:service(v7("\37\220\144\239\255\198\31\252\140\235\255\211\62\212\140\250\237\194\1","\167\115\181\226\155\138")):SendKeyEvent(false,"V",false,game);break;end end end);end break;end end end end);local v17=v12.Main:AddSection(v7("\195\55\243\83\59\85\211\236\37\226\83","\166\130\66\135\60\27\17"));local v16=v12.Main:AddToggle(v7("\105\83\250\122\55\67\70\203","\80\36\42\174\21"),{[v7("\122\25\35\118\75","\26\46\112\87")]=v7("\152\47\167\52\146\176\75","\212\217\67\203\20\223\223\37"),[v7("\158\136\174\211\175\129\188","\178\218\237\200")]=_G.Configs.Monsters[v7("\151\185\234\144\155\186\232","\176\214\213\134")]});v16:OnChanged(function(v52) local v53=0 -0 ;while true do if (v53==(1739 -(404 + 1335))) then _G.AutoMon=v52;_G.AutoD0Heart=v52;v53=3 -2 ;end if (v53==(407 -(183 + 223))) then spawn(function() while task.wait() do pcall(function() if _G.AutoD0Heart then if  not game:GetService(v7("\196\161\183\205\173\68\74","\57\148\205\214\180\200\54")).LocalPlayer.Character.HumanoidRootPart:FindFirstChild(v7("\62\242\54\63","\22\114\157\85\84")) then local v113=0 -0 ;local v114;while true do if (v113==(0 + 0)) then if (game.Players.LocalPlayer.Character:WaitForChild(v7("\236\222\30\197\83\249\161\192","\200\164\171\115\164\61\150")).Sit==true) then game.Players.LocalPlayer.Character:WaitForChild(v7("\150\225\14\68\141\177\253\7","\227\222\148\99\37")).Sit=false;end v114=Instance.new(v7("\17\93\86\239\207\54\94\93\245\240\39\75","\153\83\50\50\150"));v113=1 + 0 ;end if (v113==(338 -(10 + 327))) then v114.Name=v7("\113\121\112\23","\45\61\22\19\124\19\203");v114.Parent=game:GetService(v7("\241\30\12\236\7\98\170","\217\161\114\109\149\98\16")).LocalPlayer.Character.HumanoidRootPart;v113=2 -0 ;end if (v113==(2 + 0)) then v114.MaxForce=Vector3.new(100325 -(45 + 280) ,100338 -(118 + 220) ,96520 + 3480 );v114.Velocity=Vector3.new(0 + 0 ,449 -(108 + 341) ,0 + 0 );break;end end end else local v100=0 -0 ;local v101;while true do if (v100==(1493 -(711 + 782))) then v101=game:GetService(v7("\34\44\57\101\185\102\1","\20\114\64\88\28\220")).LocalPlayer.Character.HumanoidRootPart:FindFirstChild(v7("\29\14\209\191","\221\81\97\178\212\152\176"));wait(1 -0 );v100=1;end if (v100==(470 -(270 + 199))) then if v101 then v101:Destroy();end break;end end end end);end end);task.spawn(function() while task.wait() do pcall(function() if _G.AutoMon then local v102=game.Players.LocalPlayer;local v103=v102.Character or v102.CharacterAdded:Wait() ;local v104={workspace.Main.Boss,workspace.Main.Raid};local v105=false;for v107,v108 in pairs(v104) do for v115,v116 in pairs(v108:GetChildren()) do local v117=v116:FindFirstChild(v7("\229\242\16\250\20\194\238\25","\122\173\135\125\155"));if (v116:FindFirstChild(v7("\172\212\13\184\49\62\193\128\243\15\182\43\1\201\150\213","\168\228\161\96\217\95\81")) and v117) then if (v117.Health>(0 -0)) then v103:MoveTo(v116.HumanoidRootPart.Position);v103.HumanoidRootPart.CFrame=v116.HumanoidRootPart.CFrame * CFrame.new(0,_G.Ruo5555522k,1819 -(580 + 1239) ) * CFrame.Angles(math.rad( -(267 -177)),0 + 0 ,0 + 0 ) ;v105=true;break;end end end if v105 then break;end end if  not v105 then v103:MoveTo(Vector3.new(1.62,67.97 + 86 , -(117.88 -72)));end end end);end end);break;end end end);local v25=v12.Main:AddSlider(v7("\232\221\39\88\42\69","\55\187\177\78\60\79"),{[v7("\25\199\75\231\67","\224\77\174\63\139\38\175")]=v7("\169\78\86\61\144\68\74\110\165\85\76\47\135\74\24\28\133\79\95\43","\78\228\33\56"),[v7("\234\123\161\0\151\199\110\166\10\138\192","\229\174\30\210\99")]="",[v7("\63\232\128\80\248\49\45","\89\123\141\230\49\141\93")]=0 + 0 ,[v7("\222\120\248","\42\147\17\150\108\112")]=1954 -(1096 + 852) ,[v7("\34\167\53","\136\111\198\77\31\135")]=1187 -(645 + 522) ,[v7("\48\6\178\88\185\237\25\174","\201\98\105\199\54\221\132\119")]=1 -0 });v25:OnChanged(function(v54) _G.Ruo5555522k=v54;end);local v26=v12.Main:AddToggle(v7("\139\9\147\45\3\44\152\182\11\132\45\7","\204\217\108\227\65\98\85"),{[v7("\106\202\225\233\41","\160\62\163\149\133\76")]=v7("\228\165\29\35\194\207","\163\182\192\109\79"),[v7("\16\35\6\193\224\56\50","\149\84\70\96\160")]=_G.Configs.General[v7("\10\3\29\225\57\31","\141\88\102\109")]});v26:OnChanged(function(v55) local v56=1790 -(1010 + 780) ;local v57;while true do if ((0 + 0)==v56) then v57=0 + 0 ;while true do if (v57==(236 -(46 + 190))) then _G.A00BC=v55;spawn(function() while task.wait(95.5 -(51 + 44) ) do pcall(function() if _G.A00BC then local v120=0 -0 ;while true do if (v120==1) then game:GetService(v7("\110\30\53\82\77\22\43\111\86\7\50\82\117\22\41\71\95\18\53","\38\56\119\71")):SendKeyEvent(false,Enum.KeyCode.Return,false,game);break;end if (v120==(0 -0)) then game:GetService(v7("\148\70\195\67\31\47\67\200\176\86","\161\211\51\170\16\122\93\53")).SelectedObject=game:GetService(v7("\203\162\179\49\254\188\161","\72\155\206\210")).LocalPlayer.PlayerGui.Raid.Replay.Button;game:GetService(v7("\112\115\70\26\38\71\118\125\0\35\83\110\121\15\61\71\125\81\28","\83\38\26\52\110")):SendKeyEvent(true,Enum.KeyCode.Return,false,game);v120=1837 -(1045 + 791) ;end end end end);end end);break;end end break;end end end);print([[

	
███╗   ██╗███████╗██╗  ██╗██╗   ██╗███████╗    ██╗  ██╗██╗   ██╗██████╗ 
████╗  ██║██╔════╝╚██╗██╔╝██║   ██║██╔════╝    ██║  ██║██║   ██║██╔══██╗
██╔██╗ ██║█████╗   ╚███╔╝ ██║   ██║███████╗    ███████║██║   ██║██████╔╝
██║╚██╗██║██╔══╝   ██╔██╗ ██║   ██║╚════██║    ██╔══██║██║   ██║██╔══██╗
██║ ╚████║███████╗██╔╝ ██╗╚██████╔╝███████║    ██║  ██║╚██████╔╝██████╔╝
╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝    ╚═╝  ╚═╝ ╚═════╝ ╚═════╝ 
                                                                        ]]);v9:SetLibrary(v8);v10:SetLibrary(v8);v9:IgnoreThemeSettings();v9:SetIgnoreIndexes({});v11:SelectTab(2 -1 );v8:Notify({[v7("\199\230\76\218\32","\54\147\143\56\182\69")]="Raid กำลังทำงาน",[v7("\245\142\241\93\218\216\149","\191\182\225\159\41")]=v7("\35\6\60\69\152\221\141\100\22\33\70\136\136\208\47\92\47\82\196\140\192\46\32\125\118\163\146\228\1","\162\75\114\72\53\235\231"),[v7("\168\41\86\227\71\11\131\50","\98\236\92\36\130\51")]=152 -52 });v9:LoadAutoloadConfig();
