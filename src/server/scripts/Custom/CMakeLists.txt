# Copyright (C) 2008-2011 TrinityCore <http://www.trinitycore.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
  Custom/hunterpet_vendor.cpp
  Custom/npc_mount.cpp 
  Custom/argent_tournament.cpp
  Custom/guildmaster.cpp
  Custom/npcbuff.cpp
  Custom/professionnpc.cpp
  Custom/npc_other.cpp
  Custom/npc_title.cpp
  Custom/script_bot_giver.cpp
  Custom/cs_vip.cpp
  Custom/duel_reset.cpp
  Custom/npc_teleport.cpp
)

message("  -> Prepared: Custom")
